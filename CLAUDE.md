# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## What this repo is

Plain-text Kinesis SmartSet configuration files for a Freestyle Pro keyboard. There is no build, test, lint, or codegen step. All files are loaded onto the keyboard via Kinesis SmartSet Editor; correctness can only be verified by testing on the physical device.

## Key references

- **`AGENTS.md`** — the canonical editing guide. Read it before making any changes.
- **`README.md`** — the Action Token Dictionary (the only spec for token names like `LWIN`, `PER`, `FNSHF`, `D125`, `NULL`, etc.). Always consult before writing token sequences.

## Critical rules

**Token naming in macro bodies:** Inside `{...}` sequences, punctuation requires dictionary names — `{per}` not `{.}`, `{com}` not `{,}`, `{hyph}` not `{-}`, etc. Single letters and digits (`{a}`, `{2}`) are the exception and type as-is.

**`fn`-layer duplication:** Non-prefixed remaps (`[src]>[dst]`) only affect the base layer. If the key also needs to behave differently (or identically) on the Fn layer, add a matching `fn [src]>[dst]` line. Omitting it leaves the Fn-layer key at firmware default.

**`hk9` is the Fn key:** Binding a remap or macro to `hk9` reprograms the physical Fn key, making all `fn`-prefixed rules in that layout unreachable. Don't use `hk9` as a macro trigger in any layout that relies on `fn`-prefixed rules.

**Slot filenames are fixed:** `layouts/layout1.txt` through `layouts/layout9.txt` — SmartSet requires these exact names. Files prefixed with `_` (backups) and `test.txt` are not loaded into slots; keep them for reference.

## Layout syntax quick reference

```
[src]>[dst]          # simple remap (base layer)
fn [src]>[dst]       # remap on Fn layer only
{hk1}>{s5}{x1}{-lwin}{d}{+lwin}   # macro: speed 5, repeat 1, Win+D
```

Macro modifiers: `{sN}` = speed (1–9), `{xN}` = repeat count, `-mod`/`+mod` = hold/release modifier within sequence.

Source key names: `hk1`–`hk10`, `prnt`, `scrlk`, `hyph`, `colon`, `per`, `com`, `obrk`, `cbrk`, `apos`, `rspc`, `bspc`, and standard letter/digit/F-key names.
