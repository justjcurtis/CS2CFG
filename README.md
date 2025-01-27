# CS2 Config Repository

> feel free to fork, steal and change this config for CS2

Welcome to the CS2 Config repository! This repo contains my custom configuration files for Counter-Strike 2, including:

- A comprehensive `autoexec.cfg` for general gameplay.
- A `prac.cfg` for practice sessions.
- An `unprac.cfg` to revert practice-specific settings back to default.

This README includes installation instructions, a table of binds and aliases, and an overview of the configs.

---

## Table of Contents

1. [Installation Instructions](#installation-instructions)
2. [Configuration Files Overview](#configuration-files-overview)
3. [Table of Binds](#table-of-binds)
4. [Table of Aliases](#table-of-aliases)
5. [Features](#features)
6. [Customization](#customization)

---

## Installation Instructions

1. **Locate Your CS2 Config Folder**  
   Navigate to the folder where CS2 stores configuration files. By default, it should be:

   **Windows:**  
   `C:\Program Files (x86)\Steam\steamapps\common\Counter-Strike Global Offensive\game\csgo\cfg`

2. **Download and Add Files**  
   - Download the `autoexec.cfg`, `prac.cfg`, and `unprac.cfg` files from this repository.
   - Place all `.cfg` files into the `cfg` folder.

3. **Run the Configs**  
   - Open CS2.
   - Launch the developer console (enable it in settings if it’s not already).
   - Type the following commands to execute the respective configs:
     - `exec autoexec` (loads the main config).
     - `exec prac` (loads the practice config).
     - `exec unprac` (reverts practice changes).

---

## Configuration Files Overview

### 1. **autoexec.cfg**  
   This is the main configuration file. It contains:
   - Custom binds for gameplay, movement, and demo playback.
   - Crosshair customization commands.
   - Aliases for frequently used commands.
   - Utility commands for voice, volume control, and more.

### 2. **prac.cfg**  
   A practice configuration for grenade practice, unlimited ammo, respawns, and other utilities for training.

### 3. **unprac.cfg**  
   Reverts all practice-specific settings to their default values to return to standard gameplay.

---

## Table of Binds

| **Key**         | **Action**                                                                |
|-----------------|---------------------------------------------------------------------------|
| `=`             | Toggle crosshair size between `2.5` and `5000`.                           |
| `,`             | Switch between preset crosshairs.                                         |
| `.`             | Apply a specific crosshair preset (green, outline, dot).                  |
| `/`             | Toggle crosshair outline on/off.                                          |
| `p`             | Toggle radar scale between `0.35` and `1.5`.                              |
| `mwheeldown`    | Jump (binds scroll wheel down to jump).                                   |
| `mwheelup`      | Inspect weapon.                                                           |
| `shift`         | Duck (customized duck bind).                                              |
| `1` - `0`       | Select weapon slots.                                                      |
| `f`/`g`/`v`     | Custom slot binds for faster item switching.                              |
| `x`             | Drop bomb (or current item).                                              |
| `'`             | Drop all items.                                                           |
| `t`             | Drop current weapon.                                                      |
| `capslock`      | Voice record.                                                             |
| `MOUSE4`        | Quick switch to primary/secondary weapons.                                |
| `del`           | Set volume to `0.2`.                                                      |
| `end`           | Set volume to `0.05`.                                                     |
| `LEFTARROW`     | Skip demo back by 320 ticks.                                              |
| `RIGHTARROW`    | Skip demo forward by 320 ticks.                                           |
| `DOWNARROW`     | Set demo playback speed to `2x` (fast forward).                           |
| `UPARROW`       | Set demo playback speed to `4x` (faster forward).                         |
| `[`             | Set demo playback speed to `0.25x` (slow motion).                         |
| `]`             | Set demo playback speed to `0.5x` (half-speed).                           |
| `RSHIFT`        | Toggle pause/play for demo playback.                                      |
| `RCTRL`         | Open demo UI.                                                             |
| `o`             | Toggle noclip.                                                            |

---

## Table of Aliases

| **Alias**           | **Command(s)**                                                                |
|---------------------|-------------------------------------------------------------------------------|
| `dc`                | Disconnect from the current server.                                           |
| `x`, `q`            | Quit the game.                                                                |
| `1`                 | Execute `autoexec.cfg`.                                                       |
| `p`                 | Execute `prac.cfg`.                                                           |
| `r`                 | Execute `unprac.cfg`.                                                         |
| `crosshairswitch`   | Cycle through crosshair presets (`crosshair1`, `crosshair2`, `crosshair3`).   |
| `+dropbomb`         | Drop the bomb (or current item) with slot switching.                          |
| `+dropall`          | Drop all items.                                                               |
| `+qs`, `+hs`, `+ffw20`, `+ffw50` | Set demo playback speed to quick-switch rates (slow motion, fast forward). |
| `toggle_crosshair_outline` | Toggle crosshair outline thickness between on/off states.              |

---

## Features

- **Crosshair Customization**:
  - Easily toggle between multiple crosshair presets with binds.
  - Toggle crosshair outlines on/off for visibility.

- **Practice Configuration**:
  - Unlimited ammo, grenade trajectory preview, and impacts for easy training.

- **Demo Playback**:
  - Intuitive controls for demo playback speed and navigation.

- **Quick Volume Adjustments**:
  - Binds for switching volume levels for different environments.

- **Utility Commands**:
  - Quick commands to drop bombs, disconnect, or quit the game.

---

## Customization

Feel free to modify the binds and aliases in the provided `.cfg` files to suit your personal preferences. To add or change binds, simply edit the respective `.cfg` file with a text editor and save your changes.

For example, to change the `noclip` bind from `o` to `n`, replace:
```bind "o" "noclip"```
with:
```bind "n" "noclip"```

