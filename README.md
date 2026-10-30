# M1A2C for Gunner HEAT PC

## Description
- This mod is created by 芝士大嘴蛙（DDDDWWWWDZW）. It aims to add the M1A2C tank and its modified variants to GHPC, restoring its unique functions and armament. The initial vehicle model is retopologized by myself, based on the M1A2C model from War Thunder.
- 一个M1A2C模组，带你进入富尔达2026，用m829e4把敌人狠狠上市吧！

## Download

Use the release asset:

```text
M1A2C-1.3.2-official.zip
```


## Requirements

- **MelonLoader 0.6.x (net35)**

## Install

1. Install **MelonLoader 0.6.x (net35)** for Gunner HEAT PC.
2. Extract the `M1A2C` folder from the zip into:

```text
<GHPC install>\Bin\Mods\M1A2C
```

3. Start the game.


## Contents

- M1A2C visual model
- Independent CROWS weapon station with stabilized sight, laser rangefinder and
  ballistic elevation
- M256 120 mm gun
- M829E3 / M829E4 APFSDS and M830 / M830A1 HEAT
- Armor data and armor damage model adapted for the M1A2C
- 42-round loadout
- Optional TUSK armour with per-block hitzones and two-hit ATAR2 durability
- Gen-3 gunner thermals, 1366x768 high-power FLIR and ~20x digital zoom
- Turret-front wedge composite reinforcement
- Trophy Active Protection System as an optional feature, capable of intercepting non-kinetic projectiles travelling at roughly 1200 m/s or slower. It is mounted on both sides of the turret, with 4 rounds per side.
- Olive paint scheme fixed for this release
  <img width="2560" height="1440" alt="154a05a9064cc4af3966efe53e309610" src="https://github.com/user-attachments/assets/e19475d4-d1a7-483e-94f4-2865b7e7d9bc" />
  <img width="886" height="554" alt="image" src="https://github.com/user-attachments/assets/5391b0cd-65dd-4288-a646-32945e13160c" />
  <img width="1436" height="534" alt="image" src="https://github.com/user-attachments/assets/e7958f6a-589e-4098-ba52-36c4f78250dc" />




Relevant entries:
```ini
[ M1A2C ]

# Ammo selection
"AP Ammo (M1A2C)" = "M829e3"    # M829e2/M829e3 / M829e4
"HEAT Ammo (M1A2C)" = "M830"   # M830 / M830A1
"AP Round Count (M1A2C)" = 28
"HEAT Round Count (M1A2C)" = 14
"Vanilla Ammo Capacity (M1A2C)" = false

# Thermals / CITV
"FLIR Generation (M1A2C)" = 3
"Digital Enhancement (M1A2C)" = true
"Fixed Reticle Size (M1A2C)" = true
"CITV (M1A2C)" = true
"Rotate Azimuth (M1A2C)" = true
"Smooth CITV Panning (M1A2C)" = true

# Visuals
"LFP Armor Kit (M1A2C)" = false   # Install the lower-front-plate enhanced armour package.
"Breech Armor Kit (M1A2C)" = false   # Provides additional protection around the turret breech.
"TUSK Armor (M1A2C)" = false
"Configuration (M1A2C)" = "TUSK + APS" # Default=M1A2C, TUSK=M1A2CTUSK, or TUSK + APS=M1A2C Trophy
```

| Round | Penetration | Velocity | ERA bypass |
|---|---:|---:|---:|
| M829E2 | 680 mm | 1680 m/s | 0% |
| M829E3 | 771 mm | 1565 m/s | 60% |
| M829E4 | 847 mm | 1655 m/s | 85% |
| M830 | 550 mm | 1140 m/s | |
| M830A1 | 500 mm | 1400 m/s | |


## Features currently in development:

- 1. Selectable camouflage skins
- 2. XM1147 high-explosive rounds
- 3.Internal modeling of the 120mm cannon


## Notes

- The mod models are sourced from War Thunder. I performed retopology and re-segmented the components to adapt them for in-game functionality.All rights reserved. Redistribution, modification and commercial use
are not permitted without written permission.
- This is a compiled distribution; modify/redistribute only with permission.
- The fire control system UI is referenced from:https://github.com/thebeninator/M1A1Abrams
- The Active Protection System design references:https://github.com/AIM928/M1-Trophy
- If you wish to modify and release your own version based on my mod, please notify me.
- This mod was created with the assistance of AI   感谢蓝色大肥鱼






