# 🏺 Relic Hunter

<div align="center">

![Game Banner](https://img.shields.io/badge/Game-Relic_Hunter-brown?style=for-the-badge)
![Engine](https://img.shields.io/badge/Engine-GameMaker-green?style=for-the-badge)
![Genre](https://img.shields.io/badge/Genre-Platform_Action-orange?style=for-the-badge)
![License](https://img.shields.io/badge/License-MIT-blue?style=for-the-badge)

**An action-packed 2D platformer adventure through mysterious lands!**

[Features](#-features) • [Gameplay](#-gameplay) • [Controls](#-controls) • [Installation](#-installation) • [Credits](#-credits)

</div>

---

## 📖 About

**Relic Hunter** is a classic 2D side-scrolling platformer where you play as a brave adventurer exploring dangerous territories in search of ancient relics. Journey through three distinct environments—a lush forest, a dark cave, and an ancient temple—while fighting enemies, collecting treasures, and surviving deadly encounters.

Built with **GameMaker**, this project showcases fundamental game development concepts including physics-based platforming, enemy AI, combat systems, and level progression.

---

## ✨ Features

- 🎮 **Classic Platformer Mechanics** - Smooth jumping, running, and precise collision detection
- ⚔️ **Dual Combat System** - Melee punches and ranged pistol shooting
- 👾 **5 Unique Enemy Types** - Each with distinct behaviors and attack patterns
- 🗺️ **3 Themed Levels** - Forest, Cave, and Ancient Temple
- 💎 **Collectibles System** - Coins, ammo, and health kits scattered throughout levels
- 🎵 **Complete Sound Design** - 15 sound effects for immersive gameplay
- 📊 **Score & Health System** - Track your performance and survival
- 🏆 **Progressive Difficulty** - Each level introduces new challenges

---

## 🎮 Gameplay

### The Story
You are an adventurer traveling through dangerous lands in search of legendary relics. Each level holds a special artifact that grants you passage to the next area:
- **Level 1 (Forest)**: Find the **Pickaxe** to access the cave
- **Level 2 (Cave)**: Obtain the **Key** to unlock the temple
- **Level 3 (Temple)**: Open the **Treasure Chest** to claim victory!

### Combat Mechanics
- **Melee Attack (C)**: Quick punch that instantly defeats enemies when they're vulnerable
- **Ranged Attack (Space)**: Fire your pistol (requires ammunition)
- **Health System**: Start with 100 HP, lose 25 HP per enemy hit
- **Ammunition**: Collect ammo boxes to refill your pistol (4 bullets per box)

### Score System
- **Coins**: +1,000 points each
- **Enemy Defeated**: +300 points each
- **Survival Bonus**: Keep your health high for better scores

---

## 🎯 Collectibles

| Item | Effect | Visual Description |
|------|--------|-------------------|
| **💰 Coin** | +1,000 points | Golden coin |
| **💊 Health Kit** | Restore to 100 HP | White box with red cross |
| **📦 Ammo Box** | +4 bullets | Green ammunition crate |
| **⛏️ Pickaxe** | Level 1 completion | Mining tool |
| **🔑 Key** | Level 2 completion | Golden key |
| **📦 Treasure Chest** | Victory! | Large brown chest |

---

## 🕹️ Controls

| Key | Action |
|-----|--------|
| **W** or **↑** | Jump |
| **A** | Move Left |
| **D** | Move Right |
| **C** | Melee Punch |
| **Space** | Shoot Pistol |

---

## 🔧 Installation

### Prerequisites
- GameMaker Studio (version 1.x or compatible)
- Windows OS (recommended)

### Steps
1. Clone the repository:
   ```bash
   git clone https://github.com/isaacmendezr/Relic-Hunter.git
   ```

2. Navigate to the project folder:
   ```bash
   cd Relic-Hunter
   ```

3. Open the project file:
   ```
   relic_hunter_src/Proyecto Videojuego FINAL.project.gmx
   ```

4. Run the game in GameMaker Studio

---

## 📂 Project Structure

```
Relic-Hunter/
├── LICENSE                    # MIT License
└── relic_hunter_src/
    ├── Proyecto Videojuego FINAL.project.gmx  # Main project file
    ├── background/            # Level backgrounds (3 environments)
    ├── objects/               # Game objects (25 total)
    ├── rooms/                 # Game levels (4 rooms)
    ├── sprites/               # Character and object sprites (54+)
    ├── sound/                 # Sound effects (15 files)
    └── fonts/                 # Game fonts
```

---

## 🎵 Audio

All sound effects are free-to-use assets sourced from [Mixkit](https://mixkit.co/free-sound-effects/game/).

---

## 🛠️ Technical Details

- **Engine**: GameMaker Studio 1.x (.gmx format)
- **Game Type**: Single-player side-scroller
- **Collision**: Hitbox-based with pixel-perfect detection
- **Programming**: GML (GameMaker Language) with drag-and-drop actions

---

## 👨‍💻 Credits

**Developers**: 
- Isaac Méndez
- Jorsua Gonzalez

**Engine**: GameMaker Studio  
**Sound Effects**: [Mixkit](https://mixkit.co/free-sound-effects/game/) (Free-to-use)  
**License**: MIT License  
**Year**: 2021

---

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
