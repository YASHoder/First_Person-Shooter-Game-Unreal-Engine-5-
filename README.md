# 🎯 First Person Shooter — Unreal Engine 5

![Unreal Engine](https://img.shields.io/badge/Unreal%20Engine-5.7.4-0E1128?style=for-the-badge&logo=unrealengine&logoColor=white)
![Blueprints](https://img.shields.io/badge/Blueprints-Gameplay-1E90FF?style=for-the-badge)
![Platform](https://img.shields.io/badge/Platform-Windows-0078D6?style=for-the-badge&logo=windows&logoColor=white)
![Status](https://img.shields.io/badge/Status-In%20Development-orange?style=for-the-badge)

A **first-person shooter prototype built with Unreal Engine 5.7.4**, focused on implementing FPS combat, weapon mechanics, enemy AI, HUD systems, pickups, objectives, and gameplay feedback using Unreal Engine Blueprints.

The project started from Unreal Engine's First Person template and has been progressively expanded into a playable objective-based FPS prototype.

---

## 🎮 Full Gameplay

### ▶️ Full Gameplay Recording

**Duration:** approximately **2 minutes 54 seconds**

The complete gameplay recording used for this README is included in the project package:

**[▶️ Watch / Open Full Gameplay Video](Documentation/full-gameplay.mp4)**

> The recording demonstrates the current gameplay build, including movement, weapon combat, HUD elements, enemy encounters, reloading, objectives, and the game-over state.

### 🌐 Recommended GitHub Presentation

GitHub is not ideal for embedding a large MP4 directly in a README. For the best portfolio presentation, upload `Documentation/full-gameplay.mp4` to YouTube and use the following thumbnail link:

```markdown
[![Full Gameplay](Documentation/screenshots/combat.png)](https://www.youtube.com/watch?v=YOUR_VIDEO_ID)
```

Replace `YOUR_VIDEO_ID` with your YouTube video ID.

---

## 📸 Gameplay Screenshots

### 🌍 Gameplay Environment

![Gameplay Environment](Documentation/screenshots/environment.png)

The playable FPS arena and environment used for the current prototype.

### 🔫 Combat

![Combat](Documentation/screenshots/combat.png)

First-person weapon combat with the gameplay HUD and objective information visible.

### 🔄 Reload System

![Reload](Documentation/screenshots/reload.png)

Reload animation and weapon interaction during gameplay.

### 🤖 Enemy AI & Combat

![Enemy Combat](Documentation/screenshots/enemy-combat.png)

Enemy engagement during active combat.

### 🎯 Enemy Encounter

![Enemy AI](Documentation/screenshots/enemy-ai.png)

Close engagement with an AI-controlled enemy.

### 💥 Close-Range Combat

![Close Combat](Documentation/screenshots/close-combat.png)

First-person combat at close range.

### ☠️ Game Over

![Game Over](Documentation/screenshots/game-over.png)

Current game-over state at the end of the gameplay session.

---

# ✨ Features

## 🔫 FPS Weapon System

- First-person weapon setup
- Shooting system
- Projectile-based combat
- Weapon firing effects
- Basic reload animation
- Ammunition management
- Ammo pickup system
- Ammo pickup sound
- Aiming / iron-sight setup
- Hit detection and damage handling

## 🎯 Dynamic Crosshair

A dynamic crosshair provides visual feedback during gameplay and helps communicate the player's current combat state.

## 🔄 Reload System

The weapon includes a basic reload workflow with:

- Reload animation
- Magazine/ammunition management
- Reload interaction
- Weapon state handling

## 📦 Ammo Pickup

Ammo pickups can be collected during gameplay and restore ammunition.

## 🤖 Enemy AI

The current AI prototype includes:

- Player detection
- Enemy following/chasing
- Reaction to being hit by bullets
- Basic scouting/search behavior
- Combat interaction
- Enemy hit feedback

## 💥 Combat Feedback

Combat includes:

- Weapon firing effects
- Hit detection
- Enemy reactions
- Hit effects
- Damage interaction
- Audio feedback
- HUD feedback

## ❤️ Health & Armor HUD

The HUD provides gameplay information such as:

- Health
- Armor
- Ammunition
- Crosshair
- Timer
- Objective information

## ☠️ Kill Feed

A basic kill-feed system communicates enemy eliminations to the player.

## ⏱️ Timer

A gameplay timer is used as part of the objective-driven experience.

## 🗺️ Minimap

A live minimap helps the player understand their position and navigate the playable area.

## 🎯 Objective-Based Gameplay

The prototype uses an objective-driven gameplay loop focused on moving through the arena, engaging enemies, and clearing the required area.

```text
Start
  ↓
Explore
  ↓
Reach Objective
  ↓
Encounter Enemies
  ↓
Fight
  ↓
Reload / Collect Ammo
  ↓
Eliminate Enemies
  ↓
Complete Objective
  ↓
Game Over / End State
```

---

# 🧩 Technology Stack

| Technology | Usage |
|---|---|
| **Unreal Engine 5.7.4** | Game engine |
| **Blueprints** | Gameplay programming |
| **UMG** | User interface |
| **Unreal AI Systems** | Enemy behavior |
| **Animation System** | Reload and character animations |
| **FX Systems** | Weapon and hit effects |
| **Audio System** | Gameplay and pickup feedback |
| **First Person Template** | Initial FPS framework |

---

# 🎮 Controls

| Action | Input |
|---|---|
| Move | `W A S D` |
| Look | `Mouse` |
| Fire | `Left Mouse Button` |
| Aim | `Right Mouse Button` |
| Reload | `R` |
| Jump | `Space` |

> Controls may change as development continues.

---

# 🚀 Getting Started

## Requirements

- Windows PC
- Unreal Engine **5.7.4**
- DirectX 12-compatible GPU recommended

## Clone

```bash
git clone https://github.com/YASHoder/First_Person-Shooter-Game-Unreal-Engine-5-.git
```

## Run

1. Install Unreal Engine 5.7.4.
2. Clone the repository.
3. Open the `.uproject` file.
4. Allow Unreal Engine to generate required project files.
5. Wait for shaders/assets to compile.
6. Open the playable level.
7. Press **Play**.

Using the same Unreal Engine version used during development is recommended.

---

# 📁 Project Structure

```text
First_Person-Shooter-Game-Unreal-Engine-5-
│
├── Config/
├── Content/
│   ├── Blueprints/
│   ├── Characters/
│   ├── Weapons/
│   ├── AI/
│   ├── UI/
│   ├── Maps/
│   ├── Animations/
│   ├── Audio/
│   ├── Effects/
│   └── Assets/
│
├── .gitignore
├── *.uproject
└── README.md
```

> Exact folders may evolve as development continues.

---

# 🧠 What I Learned

This project has provided practical experience with:

- Unreal Engine 5
- Blueprint scripting
- FPS character and camera systems
- Weapon and projectile systems
- Collision and damage handling
- Health and armor
- UMG widgets
- Dynamic HUD elements
- Reload animations
- Pickup systems
- Enemy AI
- AI perception and reaction
- Combat effects
- Timers
- Objectives
- Minimap systems
- Blueprint debugging
- Asset importing
- Connecting independent gameplay systems into a complete gameplay loop

---

# 🛠️ Development Status

| System | Status |
|---|:---:|
| First Person Character | ✅ |
| Camera System | ✅ |
| Weapon System | ✅ |
| Shooting | ✅ |
| Projectile / Hit Detection | ✅ |
| Health System | ✅ |
| Armor HUD | ✅ |
| Reload Animation | ✅ |
| Dynamic Crosshair | ✅ |
| Ammo Pickup | ✅ |
| Pickup Sound | ✅ |
| Enemy AI | ✅ |
| Enemy Following | ✅ |
| Enemy Bullet Reaction | ✅ |
| Hit Effects | ✅ |
| Enemy Scouting | ✅ |
| Kill Feed | ✅ |
| Timer | ✅ |
| Minimap | ✅ |
| Basic Objective System | ✅ |
| Advanced AI Combat | 🔄 |
| Multiple Weapons | 🔄 |
| Advanced Mission System | 🔄 |
| Final Gameplay Polish | 🔄 |

---

# 🔮 Future Improvements

### Gameplay
- Multiple weapons
- Weapon switching
- Improved recoil
- Headshot system
- More enemy types
- Improved enemy attack behavior
- More objectives
- Mission progression
- Difficulty levels

### AI
- Patrol system
- Search/investigation states
- Cover system
- Advanced combat states
- Group AI behavior
- Improved navigation
- More advanced Behavior Tree logic

### UI
- Main menu
- Pause menu
- Settings menu
- Improved objective tracker
- Improved minimap
- Damage indicators
- More HUD animations

### Audio & Visuals
- Weapon sound variations
- Enemy audio
- Footsteps
- Improved muzzle flashes
- Impact effects
- Environmental audio
- Camera shake
- Additional animation polish

---

# 🎓 Project Purpose

This is an **educational and portfolio game-development project** created to gain practical experience with Unreal Engine 5 and Blueprint-based gameplay programming.

The goal is not only to make an FPS prototype playable, but also to understand how weapons, AI, UI, animation, audio, objectives, and game states work together as a complete gameplay system.

---

# 👨‍💻 Developer

**Yash Singh**

Game Developer | Unreal Engine 5 | Blueprint Development | Full Stack Developer

GitHub: [YASHoder](https://github.com/YASHoder)

---

# 📌 Repository

[First Person Shooter — Unreal Engine 5](https://github.com/YASHoder/First_Person-Shooter-Game-Unreal-Engine-5-)

---

## ⭐ Support

If you find this project interesting, consider giving the repository a ⭐.

---

> **Built with Unreal Engine 5.7.4 🎮**
>
> *Learning game development one system at a time.*
