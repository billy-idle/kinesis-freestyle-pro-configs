# Freestyle Pro User Manual (KB900)

> **Source:** `Freestyle-Pro-KB900-User-Manual-v-1.0.536-March-13-2024.pdf`
> (Kinesis official manual, March 13, 2024 edition; covers firmware through v1.0.532).
> This file is a markdown conversion for in-repo reference. The authoritative
> Action Token Dictionary lives in [`../README.md`](../README.md) — that section
> below is intentionally not duplicated here.

**Models covered:** KB900-BRN, KB900-RDQ
**Support:** www.kinesis.com/support/freestyle-pro
**Accessories:** www.kinesis.com/products/

- Palm Supports (AC903) — Detachable Palm Supports.
- VIP3 Pro Premium (AC925) — Adjustable tenting accessory and Premium Palm Supports (5°/10°/15°).
- V3 Pro (AC930) — Adjustable tenting accessory (5°/10°/15°) for use without Palm Supports.
- Palm Pads (AC700blk) — Cushioned palm pads for use with Palm Supports.
- Premium Palm Supports (AC908) — Extra thick, cushioned palm pads.

© 2024 by Kinesis Corporation, all rights reserved. Kinesis and Freestyle are
registered trademarks of Kinesis Corporation. Freestyle Pro, SmartSet, and
v-Drive are trademarks of Kinesis Corporation.

---

## Table of Contents

1. [Read Me First](#1-read-me-first)
   - 1.1 Health and Safety Warning
   - 1.2 Quick Start Guide
   - 1.3 Read This User's Manual
   - 1.4 Disable All Programming
2. [Keyboard Overview](#2-keyboard-overview)
   - 2.1 Specifications
   - 2.2 Features
   - 2.3 Package Contents
   - 2.4 System Requirements
   - 2.5 Installation
3. [Introduction](#3-introduction)
   - 3.1 Dual Layer Layouts (Embedded Fn Layer)
   - 3.2 Multimedia Actions
   - 3.3 Programming Cluster
   - 3.4 SmartSet Programming Engine — Onboard Shortcuts
   - 3.5 Adjustable Linking Cable
   - 3.6 Hotkeys
   - 3.7 Mac Users
   - 3.8 Dvorak Typists
4. [SmartSet Onboard Programming](#4-smartset-onboard-programming)
   - 4.1 Layouts
   - 4.2 Recording Macros
   - 4.3 Remapping Keys
   - 4.4 Run Status Report (SmartSet + F7)
   - 4.5 Open/Close v-Drive (SmartSet + F8)
   - 4.6 Adjust Global Macro Speed (SmartSet + F9, then number row)
   - 4.7 Enable/Disable NKRO Mode (SmartSet + Shift + F10)
   - 4.8 Soft & Hard Reset
   - 4.9 Refresh Settings (SmartSet + Layout)
   - 4.10 Program Lock (SmartSet + Shift + L)
   - 4.11 Update Firmware (SmartSet + Shift + U)
   - 4.12 Adjust Status Report Playback Speed (SmartSet + Shift + F7, then 0–4)
   - 4.13 Force v-Drive Open (SmartSet + F8 while plugging in keyboard)
5. [SmartSet Programming App for Windows & Mac](#5-smartset-programming-app-for-windows--mac)
6. [Direct Programming](#6-direct-programming)
   - 6.1 Programming Layouts
   - 6.2 Position Token Map
   - 6.3 Action Token Dictionary *(see ../README.md)*
   - 6.4 Programming Remaps
   - 6.5 Programming Macros
   - 6.6 Programming Settings
   - 6.7 v-Drive Repair
7. [Maintenance](#7-maintenance)
8. [Technical Support, Repairs, and Returns](#8-technical-support-repairs-and-returns)
9. [Warranty & Limitation of Liability](#9-warranty--limitation-of-liability)

---

## Compliance

### FCC Radio Frequency Interference Statement

This equipment has been tested and found to comply with the limits for a Class B
digital device, pursuant to Part 15 of the FCC Rules. These limits are designed
to provide reasonable protection against harmful interference when the
equipment is operated in a residential installation. This equipment generates,
uses, and can radiate radio frequency energy and, if not installed and used in
accordance with the instructions, may cause harmful interference to radio
communications. However, there is no guarantee that interference will not occur
in a particular installation. If this equipment does cause harmful interference
to radio or television reception, which can be determined by turning the
equipment off and on, the user is encouraged to try to correct the interference
by one or more of the following measures:

- Reorient or relocate the receiving antenna
- Increase the separation between the equipment and receiver
- Connect the equipment into an outlet on a circuit different from that to
  which the receiver is connected
- Consult the dealer or an experienced radio/TV technician for help

**Warning.** To assure continued FCC compliance, the user must use only
shielded interfacing cables when connecting to computer or peripheral. Also,
any unauthorized changes or modifications to this equipment would void the
user's authority to operate.

### INDUSTRY CANADA COMPLIANCE STATEMENT

This Class B digital apparatus meets all requirements of the Canadian
Interface-causing Equipment Regulations.
Cet Appareil numerique de la classe B respecte toutes les exiginces du Reglement
sur le material broilleur du Canada.

---

## 1. Read Me First

### 1.1 Health and Safety Warning

Continuous use of any keyboard may cause aches, pains or more serious
cumulative trauma disorders such as tendinitis and carpal tunnel syndrome, or
other repetitive strain disorders.

- Exercise good judgement in placing reasonable limits on your keyboarding time every day.
- Follow established guidelines for computer and workstation setup.
- Maintain a relaxed keying posture and use a light touch to press the keys.

**Keyboard is not a medical treatment.** This keyboard is not a substitute for
appropriate medical treatment! If any information in this guide appears to
contradict your health care professional's advice, please follow your health
care professional's advice.

**No warranty of injury prevention or cure.** Kinesis bases its product designs
on research, proven features and user evaluations. However, because of the
complex set of factors believed to contribute to computer-related injuries, the
company can make no warranty that its products will prevent or cure any
physical ailment. Your particular risk of injury may be affected by workstation
and chair design, posture, time worked without breaks, type of work, activities
outside the workplace, and/or individual physiology.

### 1.2 Quick Start Guide

If you are eager to get started, please consult the included Quick Start Guide.
The Quick Start Guide can also be downloaded from
www.kinesis.com/support/freestyle-pro. Consult this full User Manual for
detailed descriptions of both basic and advanced features.

For more getting started tips, visit: kinesis.com/freestyle-pro-getting-started/

### 1.3 Read This User's Manual

Even if you don't normally read manuals or you are a long-time user of Kinesis
keyboards, we strongly encourage you to review this entire manual. The Freestyle
Pro is a fully-programmable keyboard with powerful tools and features. If you
unknowingly execute a programming shortcut or key combination, you could
inadvertently alter the layout of your keyboard which might necessitate a Hard
Reset of the keyboard.

### 1.4 Disable All Programming

If you are a Windows user and QWERTY typist, and have no intention of custom
programming the keyboard, we recommend performing the simple Program Lock
command to prevent accidental reprogramming. If you change your mind down the
road you can always "unlock" programming. See Section 4.10 for details.

---

## 2. Keyboard Overview

### 2.1 Specifications

- Compact tenkeyless design with standard US ANSI key layout and embedded numeric keypad
- 6' USB cable and 20" adjustable linking cable
- 2 year limited warranty
- Dimensions: 1.25" tall × 15.5" wide × 7.25" deep
- Weight: 2.8 lbs

### 2.2 Features

- Premium Cherry® MX Brown or MX "Silent" Red mechanical switches
- Multi-platform compatibility
- SmartSet Programming Engine
- SmartSet Programming App for Windows & Mac (pre-loaded on the v-Drive)
- 9 dual-layer, fully-programmable layouts (including Mac and Dvorak)
- 4 MB onboard memory (v-Drive™)
- Multimedia controls (embedded Fn layer)
- Integrated Numeric 10-Key (embedded Fn layer)
- 8 pre-programmed hotkeys to boost productivity
- Available Game Mode, NKRO Mode, Multimodifiers, Tap-and-Hold Actions (firmware update may be required)

### 2.3 Package Contents

- Freestyle Pro mechanical keyboard
- SmartSet Programming App for Windows & Mac (pre-loaded on the v-Drive; a
  new version may be available for download — see Section 5)
- 4 Mac keycaps and keycap puller
- Quick Start Guide

### 2.4 System Requirements

- Windows® 7-11, macOS® v10.6+, Chrome OS® or Linux® & full-size USB Port

### 2.5 Installation

To install the Freestyle Pro simply plug the USB cable into a full-size USB port
on your computer. The Pro does not require the installation of any special
software or drivers or an internet connection.

---

## 3. Introduction

### 3.1 Dual Layer Layouts (Embedded Fn Layer)

The Freestyle Pro has two separate layers so each of the 95 full-size keys can
be programmed to perform two unique actions per layout, a top layer action and
an "embedded" Fn layer action. Tap the Fn key to toggle between the top layer
and the Fn layer. The Fn indicator light will illuminate while the Fn layer is
active.

Embedded actions are legended in blue. If a key does not have a secondary blue
legend, it performs the same action in both layers by default.

The Fn key can be changed to a momentary "hold" action instead of a "tap" using
the SmartSet App (see Section 5).

### 3.2 Multimedia Actions

Change your audio on the fly by accessing the 6 standard multimedia actions by
using the Fn key to toggle on the Fn layer. These multimedia actions can be
reassigned to any key on the keyboard in either layer using onboard programming
(see Section 4.3) or the SmartSet App (see Section 5).

The multimedia actions are: Mute, Volume Down, Volume Up, Play/Pause, Previous
Track, Next Track.

### 3.3 Programming Cluster

The four Programming Cluster keys enable quick and easy onboard reprogramming
(see Section 4). Tap the Layout key to toggle between the 3 primary layouts
(1, 2, and 3); the Macro key controls on-the-fly macro recording; and the Remap
key controls onboard remapping (aka rebinding).

The SmartSet Key (gear icon) controls all onboard programming shortcuts. The
two Layout LEDs indicate which layout is currently active. The Macro LED flashes
when on-the-fly macro recording is in progress. The Remap LED flashes when
onboard remapping is in progress. The SmartSet LED flashes to confirm certain
programming commands.

The four indicator LEDs in the upper right corner of the right key module are
Caps Lock, Num Lock, Scroll Lock, and the Fn Layer.

### 3.4 SmartSet Programming Engine — Onboard Shortcuts

The SmartSet key is used in conjunction with the F7-F9 & F12 keys to activate
onboard shortcuts. Onboard shortcuts are legended in white to differentiate them
from embedded Fn layer actions in blue. Additional (unlegended) onboard
shortcuts are described in Sections 4.10 - 4.15.

To trigger an onboard shortcut, first press and hold the SmartSet Key and then
tap F7-F9. To prevent against accidentally triggering the Soft Reset shortcut
you must also press and hold Shift along with the SmartSet Key before tapping
F12 ("RESET" appears in all-caps to indicate that it requires the shift key).
For a detailed explanation of onboard shortcuts see Section 4.

### 3.5 Adjustable Linking Cable

The two key modules are connected by a 20" linking cable that can be adjusted to
suit your typing preferences and body type. The basic configuration allows up to
12" of separation which is more than enough for most users.

If you need additional cable, simply remove the cable compartment cover on the
back of the left key module and thread out more of the stored cable. Once you
have achieved the desired cable length, carefully fit the excess cable into the
compartment removing any kinks and slide the cable cover on until it latches.
Rotate the left key module to remove kinks so the cable lies flat.

Position the key modules at shoulder width and/or rotate them slightly to achieve
a neutral wrist position for an ergonomically optimal typing position. Start
with a small separation or modest rotation and work your way up to the position
that feels most comfortable. For more information on typing postures visit:
www.kinesis.com/solutions/keyboard-risk-factors/

### 3.6 Hotkeys

The Freestyle Pro features 8 pre-programmed hotkeys designed to eliminate
repetitive key strokes and awkward key combinations. Layouts 1 and 3-9 are
configured for Windows users. Layout 2 is configured for Mac users.

- **Desktp:** Toggles to your desktop view.
- **Last App:** Toggles to the last active application window.
- **Select All:** Selects all text or items in the active window (application specific).
- **Undo:** Undoes the last action (application specific).
- **Cut:** Cuts the selected text to the clipboard.
- **Delete:** Deletes text to the right of the cursor.
- **Copy:** Copies the selected text to the clipboard.
- **Paste:** Pastes the selected text from the clipboard after a Cut or Copy.

### 3.7 Mac Users

Mac users should load Layout 2 by tapping the Layout Key once, and then install
the 4 Mac modifier keycaps (as shown at right) using the included keycap tool.
Layout 2 updates the four modifier keys to match a standard Mac keyboard (and
the 4 Mac keycaps), reconfigures the 8 hotkeys to work on macOS, and transforms
the Print Screen key ("PrtSc") into the Mac screen shot command. Layout 2 can be
customized using Onboard Programming or the SmartSet App.

Layout 2 is active when the right LED is on.

### 3.8 Dvorak Typists

Dvorak typists should load Layout 3 for a pre-configured Dvorak layout. Layout 3
can be customized using Onboard Programming or the SmartSet App.

Layout 3 is active when both LEDs are on.

---

## 4. SmartSet Onboard Programming

The SmartSet Engine lets you custom program the Freestyle Pro without
installing any software or special drivers on your computer. All layouts and
settings are saved directly to the v-Drive so they move with the keyboard.
There are three ways to program the keyboard: 1) Onboard Programming (all O/S),
2) the SmartSet App (Windows & Mac), and 3) Direct Programming (all O/S). Use
onboard programming to quickly build custom layouts (remaps & macros) and
adjust keyboard settings with simple onboard shortcuts.

### 4.1 Layouts (Layout or SmartSet + Number Row)

The Freestyle Pro puts 9 fully-programmable, dual-layer layouts at your
disposal. Each layout can be custom configured for different applications,
computers, or users. The two LEDs above the Layout Key indicate the active
layout.

| Layout 1 | Layout 2 | Layout 3 | Layouts 4-9 |
|:--------:|:--------:|:--------:|:-----------:|
| no LED   | right LED| both LEDs| (no steady-state LED — use Status Report) |

Tap the Layout Key to toggle through the three primary layouts (Layouts 1-3).
To jump directly to any of the nine layouts, **hold the SmartSet Key and then
tap 1-9 in the number row** to select the layout you wish to load (run a Status
Report to confirm the active layout).

### 4.2 Recording Macros

A macro is a string of characters or key actions that is triggered by a single
key press (or combo). Macros are powerful tools that can eliminate awkward key
combinations and repetitive key strokes. Macros are assigned to the active
layout when recorded and each layout can store 24 macros, each up to 300
characters long.

To record a macro on-the-fly, tap the Macro key in the Programming Cluster to
enter Macro Record Mode, choose your trigger key(s) and then type out your
macro. Tap the Macro key to stop recording.

**Macro Trigger Key(s).** After entering Macro Record Mode, the Macro LED will
flash rapidly prompting you to select a trigger key or key combination. Any
full-size non-modifier key can be used as a macro trigger. A macro can also be
triggered by a two-key combination by pairing the primary trigger key with a
modifier-key "co-trigger". To assign a key combination as a macro trigger,
first press and hold one of the six standard modifier keys (either the left or
right Ctrl, Alt or Shift) and then tap the desired primary trigger key. The
Windows key is not recommended for use as a macro co-trigger.

**Macro Contents.** After a valid macro trigger has been selected, the Macro LED
will flash slowly prompting you to begin recording your macro (open an
appropriate program during recording). Every single keystroke will be recorded
so if you make a mistake, we recommend restarting rather than using the backspace
key. To stop recording and save your macro, simply tap the Macro key. Note:
Macro Record Mode will end automatically when you hit the max length of 300
keystrokes.

The speed at which you type out the macro and pauses between keystrokes are not
recorded. The macro will playback at the Global speed setting (see Section 4.6)
by default, but the playback can be customized by adding internal timing delays
or by setting a custom playback speed for that specific macro using the SmartSet
App (see Section 5) or Direct Programming (see Section 6.5).

**Macro Playback.** To playback a macro, simply press the trigger key(s).
Modifier co-triggers should be pressed first and held while the primary trigger
key is then tapped. See Sections 4.6 and 6.5 to adjust the playback speed.

**Erasing a Macro.** To erase a macro onboard, simply tap the Macro key, then
input the trigger key(s) of the macro you wish to erase. Once the Macro LED
starts flashing slow, simply tap the Macro key again to record an "empty" macro.

**Macro Limit.** Each layout can accommodate 24 macros. When you have reached
the limit the keyboard will flash if you tap the Macro key to signal that you
must erase a macro before recording a new one. Note: Exact macro capacity
depends on the quantity and length of your macros and the keyboard firmware
version.

### 4.3 Remapping Keys

With the Remap key, you can reassign any default key action on the Freestyle
Pro to any other full-size key (in either layer) to customize the layout. The
only key that cannot be remapped onboard is the Fn key, but the Fn key can be
remapped using the SmartSet App or Direct Programming.

Tap the Remap key to enter Remap Mode. The Remap LED will flash rapidly to
prompt you to first select the "Source" key action (i.e., the key action that
you wish to assign). After selecting the Source key, the LED will flash slowly
prompting you to select the "Destination" key position (i.e., the physical key
that you wish to perform the new action). Once you select the Destination key
Remap Mode will end.

**Remapping Tips**

- Remapping is a one-way process — it creates a duplicate key action but it
  does not "swap" two key actions. To "swap" two keys you must perform two
  separate remap programming commands.
- Remapping only operates on one layer at a time. To remap the same key in
  both layers you must perform two separate remap commands, one for each layer.
- While Remap Mode is active, you can use the Fn key to navigate between layers
  as necessary if you wish to move a key action (e.g., the media keys) from the
  Fn layer to the top layer, or vice versa.
- While Remap Mode is active, the keyboard reverts back to the default
  QWERTY-Windows layout.

**Special Actions.** If you would like to assign a key action that is not
present in the default Pro layout, you can select from a menu of supported
Special Actions using the SmartSet App or Direct Programming (see Sections 5 and
6.3).

**Macro and Remap conflict.** It is possible to assign a macro and a remap to
the same physical key. In that event, the macro playback will take priority over
the remap action when you press that key, except when macros have been
temporarily disabled (see Section 4.6).

### 4.4 Run Status Report (SmartSet + F7)

Use the Status Report to "print-to-screen" a convenient report of the current
global keyboard settings. Make sure you have a text editing program (e.g.,
Notepad, Word) selected as the active window before running a Status Report.

The report contains the following fields:

| Field                            | Description                                                                     |
|----------------------------------|---------------------------------------------------------------------------------|
| `Model>`                         | Keyboard model (e.g., `FS Pro`).                                                |
| `Firmware>`                      | Firmware version and date (e.g., `1.0.0.us (4MB), 07/15/2017`).                 |
| `Active Layout>`                 | Active layout currently loaded to the keyboard (1-9).                           |
| `Remaps>`                        | Number of remapped keys in the active layout.                                   |
| `Macros>`                        | Number of macros saved to the active layout (including the hotkeys).            |
| `Macro Speed 0-9>`               | "Global" speed at which all macros are played back (see Section 4.6).           |
| `Game Mode>`                     | Game Mode status (On/Off).                                                      |
| `NKRO Mode>`                     | NKRO Mode status (On/Off).                                                      |
| `Status Report Speed 0-4>`       | Speed at which the Status Report is played.                                     |

### 4.5 Open/Close v-Drive (SmartSet + F8)

The Freestyle Pro features a 4 MB virtual drive called the "v-Drive" which is
the heart of the SmartSet Programming Engine. During normal use the v-Drive is
hidden from your computer but it can be temporarily "opened" using the onboard
shortcut to 1) run the SmartSet App (see Section 5), 2) to Direct Program
layouts and settings files (see Section 6), or 3) to install a firmware update
(see Section 4.12). Note: it is not necessary to access the v-Drive for basic
keyboard use.

When you use the onboard shortcut to connect the v-Drive your computer will now
recognize the keyboard as a Removable Storage Device called "FS PRO". The
specific appearance and location of the "FS PRO" drive on your computer will
depend on your operating system.

- **Windows:** If a pop-up doesn't appear, open File Explorer and look under
  "This PC".
- **Mac:** Look on the Desktop or under "DEVICES".
- **Linux:** Look in "MY COMPUTER".
- **Chrome:** Look in "FILES".

**Keep the v-Drive closed when not in use.** For best results, keep the v-Drive
closed when not using the SmartSet App and refrain from re-programming the
keyboard using onboard shortcuts while the v-Drive is open. Note: The
keyboard's multimedia and mouse actions are disabled while the v-Drive is open,
and some Onboard Shortcuts may also be disabled.

**Closing the v-Drive.** Before disconnecting the v-Drive, always save your
work, close all `.txt` files and the SmartSet App, and eject the drive from your
Operating System by right-clicking it and selecting the "Eject" option. Then,
use the same v-Drive shortcut to disconnect the v-Drive (LEDs will flash) to
resume normal operating mode, or you can simply unplug the keyboard. Note: Mac
users can safely ignore the "Device Not Ejected Properly" message.

### 4.6 Adjust Global Macro Speed (SmartSet + F9, then number row)

The Freestyle Pro can playback macros at one of nine different speeds, ranging
from a super-slow 4 characters-per-second (CPS) up to a blazing fast 3,000 CPS!
The default Global speed is Speed 5, which is good for text macros but might be
too fast or slow for certain key combinations depending on your computer and the
application. To adjust the Global speed, use the onboard shortcut to enter Macro
Speed Mode and then use the number row to select a speed from 1-9. If you wish
to temporarily disable macro playback without deleting any macros, choose "0"
instead.

| Setting                | Speed 1 | Speed 2 | Speed 3 | Speed 4 | Speed 5 (default) | Speed 6 | Speed 7 | Speed 8 | Speed 9 |
|------------------------|---------|---------|---------|---------|--------------------|---------|---------|---------|---------|
| Actions Per Second     | 4       | 8       | 12      | 22      | 35                 | 62      | 85      | 125     | 250     |
| Words Per Minute       | 48      | 96      | 144     | 264     | 420                | 744     | 1,020   | 1,500   | 3,000   |

\*Playback speeds are approximate. Exact speeds will depend on the length of
the macro, your computer, and the active application.

Note: You can override the Global speed setting and assign a custom, individual
playback speed for any given macro using the SmartSet App (see Section 5) or
Direct Programming (see Section 6.5).

### 4.7 Enable/Disable NKRO Mode (SmartSet + Shift + F10)

NKRO ("n-key rollover") mode is a special operating mode that allows the
keyboard to register all simultaneous key-presses. Most standard keyboards limit
the number of keys you can press at one time to six (aka "6KRO"). If you press
more than 6 keys at a time on a 6KRO keyboard, the keyboard may fail to register
some of those key-presses. 6KRO is fine for basic typing and will work for most
keyboard users a majority of the time, but some keyboard enthusiasts prefer NKRO
for maximum performance. Use the onboard shortcut to toggle NKRO Mode on and off
(the Pro will take a second to re-enumerate). NKRO mode will remain in effect
until keyboard is unplugged or the v-Drive is opened. Confirm NKRO mode with the
Status Report.

### 4.8 Soft & Hard Reset

**Soft Reset (SmartSet + Shift + F12).** Use the Soft Reset onboard shortcut to
erase all remaps and macros in both layers of the active layout. Note: Soft
Reset will also erase the default macros assigned to the 8 hotkeys. The "Reset"
legend is capitalized to remind you that you need to combine the Shift key with
the SmartSet key to protect you from accidentally performing a Soft Reset.

**Hard Reset (SmartSet + F12 while plugging in keyboard).** Use the Hard Reset
onboard shortcut to restore all nine layouts to the QWERTY Windows configuration
and to restore the Pro to its factory default settings. Note: Backup Mac and
Dvorak layouts are not affected by either a Soft or Hard Reset.

### 4.9 Refresh Settings (SmartSet + Layout)

The Refresh shortcut is a very important tool if you are programming the keyboard
using the SmartSet App or Direct Programming. Unlike conventional keyboard
software that uses custom drivers, the SmartSet App is driverless and does not
update the keyboard settings dynamically. Normally changes made do not go into
effect until the v-Drive is disconnected, but you can use the Refresh onboard
shortcut to implement any saved changes immediately.

### 4.10 Program Lock (SmartSet + Shift + L)

Use the Program Lock onboard shortcut to temporarily deactivate all of the
Programming Cluster keys. To disable Program Lock use the same onboard shortcut.
If you have no plans to reprogram the keyboard, or have successfully programmed
the keyboard to your liking, we highly recommend engaging the Program Lock to
prevent accidental reprogramming.

Note: Indicator LEDs flash 4× upon Lock, and 2× upon Unlock.

### 4.11 Update Firmware (SmartSet + Shift + U)

Periodically Kinesis will release new versions of firmware for the Freestyle Pro
with new features and bug fixes.

Check here for firmware updates: www.kinesis.com/support/freestyle-pro/#firmware-updates

Installing new firmware is quick and easy:

1. Obtain a valid Freestyle Pro firmware file (`.upd` file) from the URL above.
2. Connect the v-Drive (SmartSet + F8).
3. Save the new firmware file inside the `firmware` subfolder on the v-Drive.
4. Rename the firmware file `update.upd`.
5. Disconnect the v-Drive (SmartSet + F8).
6. Press `SmartSet + Shift + U` to initiate the update.

If a valid firmware file has been renamed properly and saved to the correct
location, the keyboard will flash and the lights will go off for 10-12 seconds.
The keyboard will then re-enumerate with the new firmware.

Run a Status Report to confirm the new firmware has been installed correctly.
Note: Custom layouts and settings are not affected by a firmware update.

### 4.12 Adjust Status Report Playback Speed (SmartSet + Shift + F7, then 0-4)

Certain computers may have problems playing the Status Report. If you are
experiencing dropped characters you can try a slower playback speed. Use the
onboard shortcut to enter Status Speed Mode (LEDs will flash), then tap "1-4"
to select a different speed (default speed is 3), or "0" to disable the Status
Report altogether.

### 4.13 Force v-Drive Open (SmartSet + F8 while plugging in keyboard)

If you wish to have the v-Drive open when you plug in the keyboard, or are
having difficulty accessing the v-Drive with the normal shortcut, simply hold
down this shortcut while plugging in the keyboard.

---

## 5. SmartSet Programming App for Windows & Mac

The SmartSet App lets you design and edit custom layouts, build powerful macros,
and customize keyboard settings. The App works in conjunction with onboard
programming, but it has several additional tools for power users. The App can
be run from any Windows or Mac computer and all settings are saved directly to
the keyboard for use on all Operating Systems.

- **Special Actions:** F13-F24, mouse actions, Fn "Shift", numeric keypad
  actions, Dvorak/Colemak layouts and more.
- **Macro tools:** individual playback speeds, multiplay, Windows combinations,
  timing delays, or choose from various pre-configured macros.
- **Tap-and-Hold Actions:** Assign two distinct actions to a single, non-typing
  key (example: hold the Shift key for Shift, or tap it for Escape).
  \*\*\*Firmware update required.
- **Multi-modifiers:** Assign the Hyper or Meh multi-modifier keys for
  conflict-free, system-wide shortcuts using third-party software.
  \*\*\*Firmware update required.

**Launching the App.** Use the onboard shortcut to connect the v-Drive, then
locate and open the "FS Pro" removable drive (see Section 4.5 for details). The
v-Drive is pre-loaded with a Windows version and a 32-Bit Mac version of the
SmartSet App. Select the appropriate version of the App based on the Operating
System of the connected computer. Be sure to save your changes in the App, and
then close the App and eject the v-Drive in your O/S before disconnecting the
v-Drive using the onboard shortcut.

Note: Mac users who have upgraded to a 64-bit version of macOS will need to
download the 64-bit version of the SmartSet App at the URL below.

**Downloading New Versions.** Newer versions of the App may be available here:
www.kinesis.com/support/freestyle-pro/#smartset-app

**Detailed App Usage Instructions.** For detailed App programming instructions
consult the Freestyle Pro SmartSet App Manual available here:
www.kinesis.com/support/freestyle-pro/#manuals

---

## 6. Direct Programming

The keyboard's layouts and settings are stored on the v-Drive as a series of
simple text files (`.txt`), which can be accessed in Windows, Linux, Mac, and
Chrome. Each time a remap or macro is created, it is written to the
corresponding layout `.txt` file as a discrete line of "code". Each time a
keyboard setting is changed, the change is recorded in the appropriate field in
the `kbd_settings.txt` file. Users can edit these files directly to customize
keyboard layouts and settings. For those who do not have a computer that can run
the SmartSet App, Direct Programming is a way to access the various power-user
tools which are not otherwise available through onboard programming.

**Eject v-Drive before closing (Windows Users).** After editing any `.txt`
files on the v-Drive, it is necessary to first save and close the files, and
then use the Windows eject protocol before closing the v-Drive. Right-click the
"FS PRO" removable drive in File Explorer and select Eject. Once you receive the
"Safe to Eject" notification you may proceed to closing the v-Drive with the
onboard shortcut. Failure to eject can result in a minor drive error that
Windows will ask you to repair (see Section 6.7).

**Non-US Users.** Your computer must be configured for the English (US) keyboard
layout. Other language drivers use different codes/positions for certain keys
which are critical for programming characters such as `[]`, `{}` and `>`.

### 6.1 Programming Layouts

The nine default layouts are saved as separate `.txt` files in the `layouts`
subfolder. Each layout is based on the default PC key configuration and displays
the 8 pre-programmed hotkeys. Additional remaps and macros are saved to specific
layout files.

Layout 2 has been customized for Mac users and Layout 3 for Dvorak typists.
Deleting a layout file will permanently delete its custom remaps & macros, but
the keyboard will automatically regenerate a QWERTY layout file with the 8
standard Windows hotkeys. Backup Mac and Dvorak layouts are included in the
layouts subfolder for your reference, since a Reset will always restore Layout 2
or Layout 3 as the QWERTY Windows default.

**File Naming Convention.** Only the numbered layouts can be loaded to the
keyboard. Additional backup layouts can be saved with descriptive names, but
they cannot be loaded without first renaming them.

**Syntax Overview.** Remaps and macros are encoded in a layout file using a
basic syntax. Each of the 95 full-size keys on the keyboard has been assigned a
unique "Position" token used to identify it during programming (see Section 6.2).
Each keyboard & mouse action supported by the Pro has been assigned a unique
"Action" token corresponding to a standard USB "scan code" (see Section 6.3).
Each line of code must include a position token and one or more action tokens.
The `>` symbol is used to separate position tokens from action tokens, and
individual tokens are surrounded by brackets.

Examples:

- Remaps are encoded with square brackets: `[position]>[action]`
- Macros are encoded with curly brackets: `{position1}{position2}>{action1}{action2}{action3}...`

**Layout Programming Tips**

- Position tokens are always based on the default QWERTY Windows layout.
- If the keyboard cannot understand the desired remap, then the default action
  will remain in effect.
- Do not mix and match square and curly brackets in a single line of code.
- Separate each line of code with Enter/Return.
- The order in which the lines of code appears in the `.txt` file does not
  generally matter, except in the event of conflicting commands, in which case
  the command closest to the bottom of the file will be implemented.
- Tokens are not case-sensitive (see Section 6.5).
- A line of code can be temporarily disabled by placing an asterisk (`*`) at the
  beginning of the line.

### 6.2 Position Token Map

**Top Layer Position Tokens.** Each of the 95 full-size keys on the keyboard has
a unique position token based on the default QWERTY Windows layout. (The PDF's
graphical keyboard map is not reproduced here — consult the official PDF for
the visual diagram.)

**Fn Layer Position Tokens.** In general, to designate a key position in the
Fn layer, you simply encode the prefix `fn` (with a space) before the basic,
top-layer token (outside the brackets). Keys with a unique embedded key action
have different Fn-layer position tokens, as shown in the PDF diagram.

### 6.3 Action Token Dictionary

The Action Token Dictionary is maintained in this repository as the
authoritative spec at [`../README.md`](../README.md) (see AGENTS.md). Refer to
that file for the full tables of alphanumeric, function-key, modifier,
punctuation, multimedia/mouse, editing/navigation, numeric-keypad, and
miscellaneous action tokens.

### 6.4 Programming Remaps

To program a remap, encode the position token and the action token in square
brackets, separated by `>`.

**Remap examples:**

1. Hotkey 1 performs `Q`:
   `[hk1]>[q]`
2. Escape key performs Caps Lock:
   `[esc]>[caps]`
3. The Windows key in the Fn layer performs Right Shift:
   `fn [lwin]>[rshft]`
4. `F1` in the embedded layer performs Tab:
   `fn [mute]>[tab]`

### 6.5 Programming Macros

**Shifted Actions.** To produce a shifted key action, it is necessary to encode
a macro which includes both the down and up stroke of the shift key surrounding
the basic key action. Downstrokes are indicated by placing a `-` inside the
bracket and upstrokes are indicated by placing `+`. See example 1 below.

**Individual Playback Speed Prefix `{s_}`.** By default, all macros play at the
selected "Global" playback speed. To assign a custom speed for improved playback
performance for a given macro you can use the "Individual Playback Speed" prefix
`{s_}`. Choose a number from 1-9 corresponding to the speed scale shown in
Section 4.6. The speed prefix should be placed to the right of the `>` before
the macro content. See example 2 below.

**Multiplay Prefix `{x_}`.** By default, all macros playback continuously while
the trigger key is held. To override the repeat feature and restrict a macro to
playback a specific number of times you can use the "Macro Multiplay" prefix
`{x_}`. Choose a number from 1-9 corresponding to the number of times you want
the macro to replay. The multiplay prefix should be placed to the right of the
`>` before the macro content. See example 3 below.

> If a macro is not playing back properly, try assigning a Multiplay value of 1.
> The macro may actually be firing multiple times before you are releasing the
> trigger key.

**Delays.** Delays can be inserted into a macro to improve playback performance
or to produce a mouse double-click. Delays are available in 125 and 500
millisecond increments (`{d125}` & `{d500}`). Delay tokens can be combined to
produce delays of various durations and inserted at any point in a macro. See
example 4 below.

**Macro examples:**

1. Pause key performs "Hello" with a capital H:
   `{pause}>{-lshft}{h}{+lshft}{e}{l}{l}{o}`
2. Hotkey 5 performs "qwerty" at speed 9:
   `{hk5}>{s9}{q}{w}{e}{r}{t}{y}`
3. Hotkey 1 increases the volume 3 notches:
   `{hk1}>{x3}{vol+}`
4. Tab key performs a left-mouse double click:
   `{tab}>{lmous}{d125}{lmous}`

### 6.6 Programming Settings

**Keyboard Settings.** The current global settings for the keyboard are saved in
the `kbd_settings.txt` file in the `settings` sub-folder. Users can update these
settings by modifying the fields in this `.txt` file and then using the Refresh
shortcut (SmartSet + Layout) to implement them.

| Field              | Description                                                                                          | Example              |
|--------------------|------------------------------------------------------------------------------------------------------|----------------------|
| `startup_file`     | Edit the name of the `.txt` file to instruct the keyboard to load a different active layout.         | `startup_file=layout1.txt` |
| `macro_speed`      | Change the Global Macro Speed (see Section 4.6) with `1-9` for speed, or `0` to disable (default 5).| `macro_speed=9`      |
| `game_mode`        | Disable Game Mode with `OFF` or enable with `ON` (see Section 4.8).                                  | `game_mode=OFF`      |
| `nkro_mode`        | Disable NKRO Mode with `OFF` or enable with `ON` (see Section 4.7).                                  | `nkro_mode=OFF`      |
| `status_play_speed`| Change the Status Report Playback speed (see Section 4.12) with `1-4` for speed, or `0` to disable (default 3). | `status_play_speed=3` |
| `program_key_lock` | Disable Program Locking with `OFF` or enable with `ON` (see Section 4.11).                           | `program_key_lock=OFF` |
| `v_drive`          | Force the v-Drive to open automatically every time the keyboard is plugged in with `auto`, or require manual opening with `manual`. | `v_drive=manual` |

**SmartSet App Settings.** In the `settings` sub-folder you may also notice the
`app_settings.txt` file. This file stores your saved preferences for in-App
notifications when using the SmartSet App. "On" disables the notification and
"Off" enables the notification.

| Field              | Example            |
|--------------------|--------------------|
| `app_intro_msg`    | `app_intro_msg=on`|
| `saveas_msg`       | `saveas_msg=off`   |
| `save_msg`         | `save_msg=on`      |
| `multiplay_msg`    | `multiplay_msg=off`|
| `speed_msg`        | `speed_msg=off`    |
| `copy_macro_msg`   | `copy_macro_msg=off`|
| `reset_key_msg`    | `reset_key_msg=off`|

### 6.7 v-Drive Repair

If you forget to eject the v-Drive after Direct Programming on a Windows PC as
described in Section 6.0, the next time you open the v-Drive on a Windows
computer you may receive a harmless drive error warning. If you receive this
error, follow the prompts to quickly "repair" the drive.

---

## 7. Maintenance

To keep your Freestyle Pro performing at its peak, we recommend periodically
spraying canned air between the keycaps to remove any loose debris and wiping it
clean with a damp, soft cloth (no soap).

---

## 8. Technical Support, Repairs, and Returns

For FAQs, troubleshooting tips and links to other resources visit:
www.kinesis.com/support/freestyle-pro/.

Kinesis offers free, lifetime technical support on all of our devices. Please
submit a ticket and provide all of the requested information so we can diagnose
your issue as fast as possible. Submit a ticket here:
www.kinesis.com/support/contact-a-technician/

**Return Merchandise Authorizations ("RMAs").** For any repair, regardless of
warranty coverage, you must first contact Kinesis Technical Support to obtain a
Return Merchandise Authorization ("RMA").

**Repairs.** This product must be repaired by authorized personnel only.
Unauthorized repairs may seriously jeopardize the safety of the user (such as
from fire danger) and will invalidate your warranty.

**Packaging and Shipping.** To ship a product back to Kinesis please use its
original packaging or other suitable packaging that protects the device against
impact and shock. You should insure the package with your carrier as Kinesis is
not responsible for items until they are received at the Kinesis repair center.
Packages sent to Kinesis without an RMA number marked on the outside of the box
may be refused.

---

## 9. Warranty & Limitation of Liability

Visit www.kinesis.com/warranty for the current terms of the Kinesis Limited
Warranty. Kinesis does not require any product registration to obtain warranty
benefits. Proof of purchase is required for warranty repairs.

**Disclaimer of Other Warranties.** The warranty and remedies described in the
Kinesis Limited Warranty referenced above are exclusive and in lieu of all
others, whether oral or written, express or implied. Kinesis specifically
disclaims any and all implied warranties, including, without limitation,
warranties of merchantability and fitness for a particular purpose. No Kinesis
dealer, agent, reseller, or employee is authorized to make any modification,
extension, or addition to this warranty. Kinesis does not warrant that the
product will meet your requirements, or that operation of the product will be
uninterrupted or error-free, or that all errors will be corrected.

**Limitation of Liability.** Kinesis is not responsible for special, incidental,
or consequential damages resulting from any breach of warranty, or under other
legal theory, including but not limited to lost profits, downtime, goodwill,
damage to or replacement of equipment and/or property nor any costs of
recovering, reprogramming, or reproducing any program or data stored in or used
with Kinesis products.