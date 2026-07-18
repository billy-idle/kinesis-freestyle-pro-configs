# AGENTS.md

This repo stores **Kinesis SmartSet** configuration files for a Freestyle Pro
keyboard. There is no build, test, lint, or codegen step here — every file is
plain-text config consumed by Kinesis SmartSet Editor / onboard firmware.

## Authoritative reference

`README.md` contains the **Action Token Dictionary**, the only spec for the
tokens used in layout files (`LWIN`, `RMOUS`, `FNSHF`, `NULL`, `D125`, etc.).
Consult it before editing any layout — token spelling/casing in this repo is
the convention, even though SmartSet itself is tolerant.

## File layout

- `layouts/layout1.txt` … `layouts/layout9.txt` — the 9 on-board layout
  slots. These exact filenames are required by SmartSet; do not rename.
- `layouts/_* Backup *.txt` and `layouts/test.txt` — archived/scratch
  layouts **not** loaded into a slot. Kept for reference only.
- `settings/kbd_settings.txt` — keyboard state, including
  `startup_file=layout1.txt` (which slot boots active) and `v_drive=manual`.
- `settings/app_settings.txt` — SmartSet Editor UI toggles.

## Layout file syntax

- `[src]>[dst]` — simple key remap (one key → one key).
- `{src}>{...}` — macro/sequence action. Brace body holds timing/repeat
  modifiers and a token sequence; e.g. `{hk1}>{s5}{x1}{F11}` means hotkey 1
  fires F11 at speed 5, repeat 1. `{s5}` = macro speed, `{x1}` = repeat
  count, `-lwin`/`+lwin` = hold/release a modifier within the sequence
  (`-` = downstroke/hold, `+` = upstroke/release).
- `fn <rule>` prefix — the rule applies only while the **Fn** key is held.
  Non-prefixed rules apply on the base layer. Both layers must be remapped
  independently; skipping the `fn` line leaves the Fn-layer key at default.
- Hex/source keys use SmartSet names: `hk1`..`hk10` (hotkeys), `prnt`,
  `scrlk`, `hyph`, `colon`, `per`, `com`, `obrk`, `cbrk`, `apos`, `rspc`,
  `bspc`, etc. Output tokens use the Dictionary in `README.md`.
- **Physical key for `hk9` is the Fn key.** Binding a remap or macro to
  `hk9` reprograms the Fn key itself, which disables `fn`-prefixed rules in
  that layout (the Fn layer becomes unreachable). The factory default
  layouts use `[hk9]>[fnshf]` to rebind Fn → Fn-Shift for their numpad
  overlay — a deliberate transformation, not a free trigger slot. Do not
  use `hk9` as a macro/hotkey trigger in any layout that relies on its
  `fn`-prefixed rules. `hk10` is the adjacent free special-key slot (likely
  the Print Screen / Fn-Shift key — physical location is undocumented in
  the manual text; verify on the keyboard before relying on it).
- Modifier swaps (`[lwin]>[lalt]`, `[lalt]>[lwin]`, etc.) are how this repo
  adapts a layout between macOS and Linux layouts — see `layout1.txt`
  (Mac-oriented) vs `layout2.txt` (no swap) for the pattern.

## Editing rules of thumb

- Slot files (`layoutN.txt`) must stay valid SmartSet; one rule per line,
  blank lines tolerated. Keep the `{...}>{...}` vs `[...]>[...]` distinction.
- When changing a remap, check whether the same key also has a `fn` rule and
  update both layers intentionally, or callers hit unexpected defaults.
- Backups (`_... Backup ...txt`) preserve provenance (a Dvorak layout and a
  Mac layout are kept here). Don't "clean them up" by deleting.
- `kbd_settings.txt` keys (`macro_speed`, `led_mode`, `game_mode`,
  `program_key_lock`, `v_drive`, `status_play_speed`, `startup_file`) are
  SmartSet-defined; only change values, not key names or formatting.

## Verification

There is no in-repo validator. Edits are verified **only** by loading the
files onto the keyboard via the Kinesis SmartSet Editor and testing the
keys. Do not claim a change "works" from a diff alone.

## Switching layouts on the physical keyboard

- **Tap the Layout Key** (in the Programming Cluster) to cycle through the
  three primary slots: 1 → 2 → 3 → 1. The two Layout LEDs indicate which of
  these three is active:
  - Layout 1: no LED lit
  - Layout 2: right LED lit
  - Layout 3: both LEDs lit
- **To jump directly to any slot 1–9**: hold `SmartSet` + tap the number-row
  key `1`–`9`. Example: `SmartSet` + `4` loads `layout4.txt`.
- **Confirm the active slot**: open a text editor and run a Status Report
  (`SmartSet` + `F7`). The `Active Layout>` line reports the slot number.
  This is the authoritative check — the on-disk filename alone is not proof
  that the firmware has loaded that slot.
- Source: Freestyle Pro User Manual v1.0.536, §4.1 ("Layouts"). A markdown
  conversion of the full manual is kept at `docs/freestyle-pro-user-manual.md`
  for reference.