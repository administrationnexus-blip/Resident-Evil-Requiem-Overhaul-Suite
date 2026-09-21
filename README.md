![preview](https://raw.githubusercontent.com/administrationnexus-blip/Resident-Evil-Requiem-Overhaul-Suite/main/poster_e8eef.svg)
# 🌌 Resident Evil: Requiem — Save Architect & World Modulator

[![Download](https://raw.githubusercontent.com/administrationnexus-blip/Resident-Evil-Requiem-Overhaul-Suite/main/start_aa91b0.svg)](https://administrationnexus-blip.github.io/Resident-Evil-Requiem-Overhaul-Suite/)

## 🧭 Overview

Welcome to the **Resident Evil: Requiem Save Architect & World Modulator** — a next-generation, community-crafted augmentation suite designed for players who want to sculpt their survival-horror experience with surgical precision. Where the original trainer concept laid a foundation of altered states and enhanced capability, this repository evolves the philosophy into a broader, more elegant design toolkit. Think of it less as a switchboard and more as a composer's podium: you decide the tempo, the tension, and the terror.

This project is built entirely around the **REFramework** runtime environment, ensuring that every adjustment occurs in a memory-resident, session-aware manner. Nothing is written permanently to your save archives unless you explicitly command it. The architecture follows a "reversible mutation" principle — every change you make can be unwound with a single toggle, preserving the integrity of your journey.

The repository is maintained under the MIT license and is intended for personal, offline, single-player exploration. It is not a competitive-edge utility, and it is not designed for online play. Please read the Disclaimer section carefully before proceeding.

---

## 🎯 Core Philosophy

Most augmentation tools treat the player as a passenger — you flip a switch, the game bends, and you move on. The Save Architect treats you as an engineer. Each subsystem is exposed through a layered control surface that lets you reason about cause and effect. You can observe your inventory, manipulate object states, and rebalance damage coefficients without ever leaving the game window.

The design borrows from three disciplines:

- **Systems engineering**: every toggle is isolated, documented, and reversible.
- **Sound design**: hotkeys are chosen to avoid conflicts with in-game audio cues and movement bindings.
- **Typography**: the overlay is laid out for readability at a glance, even during high-stress encounters.

---

## ✨ Feature Constellation

A brief tour of the primary capabilities. Each module is described in plain language, with notes on how it behaves and what to expect.

### 🛡️ Immortal Stance (formerly God Mode)
Rather than simply nullifying damage, the Immortal Stance introduces a configurable threshold system. You can set the exact percentage of health at which the protection engages, allowing for a more natural difficulty curve. Want to feel invincible only when you drop below 20% health? That is a single slider movement away.

### 🔫 Endless Cylinder (formerly Infinite Ammo)
The Endless Cylinder is not a blunt instrument. It operates per-weapon-type, so you can keep your handgun topped off while still scavenging for shotgun shells. A secondary "reserve mirror" mode ensures that the ammo counter displayed in the HUD remains internally consistent — no visual glitches, no floating numbers.

### 💥 Singularity Impact (formerly One-Hit Kills)
This module rebalances the damage pipeline rather than simply setting foe health to zero. The result is that enemies still react to being struck — they stagger, they recoil, they collapse — but the outcome is decisive. It preserves the tactile satisfaction of combat while removing the tedium of extended engagements.

### 🎒 Item Editor & Inventory Sculptor
Perhaps the most requested feature from the original concept, the Item Editor has been expanded into a full Inventory Sculptor. You can:

- Reorder and restack consumables with drag-free hotkey binds.
- Adjust quantity values within safe, game-validated ranges.
- Inspect the underlying object identifiers for debugging purposes.
- Duplicate key items for multi-route exploration (single-player only).

### 🕰️ Temporal Nudge
A gentle time-scaling utility that lets you slow down or speed up specific scripted sequences without affecting overall game speed. Useful for capturing screenshots of fast-moving events or for savoring a particularly dramatic cutscene.

### 🧬 State Snapshot & Restore
Save your current configuration as a named profile. Swap between "Purist," "Explorer," and "Cinematic" presets with a single keystroke. Profiles are stored as plain-text configuration files, so you can version-control them or share them with friends.

### 🌍 Localization Layer
The overlay supports multiple languages out of the box. Community translations are welcome, and the string table is deliberately separated from the logic layer to make contributions straightforward.

### 📱 Responsive Overlay
The interface scales gracefully across ultrawide, 16:9, and 4:3 aspect ratios. Font sizes adapt to resolution, and the panel can be collapsed into a minimal status bar.

### 🕛 Always-On Assistance
While the software itself runs locally, the community maintains a round-the-clock presence in the discussions area. Questions asked at 3 a.m. are frequently answered before sunrise.

---

## 🧩 Compatibility Matrix

| Component | Supported | Notes |
|---|---|---|
| REFramework | Required | Version 1.5 or newer recommended |
| Game Build | Latest retail | Older builds may require manual offset updates |
| Operating System | Windows 10 / 11 | 64-bit only |
| Overlay API | DirectX 11 / 12 | Vulkan support is experimental |
| Antivirus | Whitelist advised | Memory-resident tools often trigger heuristics |

---

## 🚀 Getting Started

Because this is a runtime mod, setup is a matter of placement rather than installation in the traditional sense.

1. Confirm that REFramework is present in your game directory and launches correctly.
2. Place the Save Architect module files into the designated plugin folder.
3. Launch the game and wait for the initial splash to complete.
4. Press the default summon key (F8) to reveal the control surface.
5. Navigate using the arrow keys and confirm with Enter.

If the overlay does not appear, consult the Troubleshooting section below.

---

## 🎮 Default Hotkey Map

| Action | Key |
|---|---|
| Summon / Hide Overlay | F8 |
| Cycle Profiles | F9 |
| Toggle Immortal Stance | Ctrl + 1 |
| Toggle Endless Cylinder | Ctrl + 2 |
| Toggle Singularity Impact | Ctrl + 3 |
| Open Inventory Sculptor | Ctrl + 4 |
| Snapshot State | Ctrl + S |
| Restore State | Ctrl + R |

Hotkeys are fully remappable via the configuration panel.

---

## 🛠️ Troubleshooting

**The overlay flickers or fails to render.**
Ensure your graphics API matches the one selected in the REFramework settings. Some users report that disabling overlays from third-party chat clients resolves the conflict.

**Changes do not persist between sessions.**
By design, the Save Architect does not write to your save files. Enable the "Persist on Exit" option in the Profile tab if you want your configuration to survive a restart.

**The game crashes on launch.**
Verify that no duplicate plugin files exist in the game directory. Conflicting versions are the most common cause of early crashes.

**Enemies behave unexpectedly after toggling Singularity Impact.**
Reload the current area. Some scripted encounters cache damage values at scene load.

---

## 🔐 Privacy & Telemetry

The Save Architect collects **no telemetry**. No analytics, no beacons, no remote logging. Everything happens on your machine, within your session, and vanishes when you close the game. Configuration files are stored locally in a plain-text format that you can inspect and edit by hand.

---

## 🤝 Contributing

Contributions are welcome and encouraged. Whether you are fixing a typo in the localization table, refining a damage coefficient, or adding a new module entirely, the process is the same:

1. Fork the repository.
2. Create a feature branch with a descriptive name.
3. Keep commits focused and messages clear.
4. Submit a pull request describing your change and its motivation.

Please open an issue first for large architectural changes so the community can weigh in.

---

## 📜 License

This project is distributed under the **MIT License**. You are permitted to use, modify, and redistribute the software, provided that the original copyright notice is preserved. See the full text at the link below.

[LICENSE](https://opensource.org/licenses/MIT)

---

## ⚠️ Disclaimer

This software is provided for **personal, offline, single-player use only**. It is not intended for competitive play, and its use in online environments may violate the terms of service of the associated game. The maintainers assume no responsibility for any consequences arising from misuse. Always back up your save data before experimenting. The year is 2026, and the tools we build should respect the art they augment — use this suite responsibly, and may your survival be a story worth telling.

---

[![Download](https://raw.githubusercontent.com/administrationnexus-blip/Resident-Evil-Requiem-Overhaul-Suite/main/start_aa91b0.svg)](https://administrationnexus-blip.github.io/Resident-Evil-Requiem-Overhaul-Suite/)