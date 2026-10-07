# 🎯 First Person Shooter — Unreal Engine 5

A **first-person shooter prototype developed in Unreal Engine 5.7.4**, focused on learning and implementing core FPS gameplay systems, weapon mechanics, enemy AI, combat feedback, HUD elements, and objective-based gameplay using Unreal Engine Blueprints.

The project started from the **Unreal Engine First Person template** and is being progressively expanded into a complete playable FPS experience.

---

## 🎮 Project Overview

This project is a learning-focused FPS prototype built to explore the major systems required in a modern first-person shooter.

The gameplay revolves around controlling a first-person character, using a firearm, managing ammunition, fighting AI-controlled enemies, completing objectives, and receiving real-time gameplay feedback through the HUD.

The project is being developed incrementally, with each system added and tested as part of the development process.

### Current Gameplay Loop

```text
Start Game
    ↓
Explore the Environment
    ↓
Locate / Encounter Enemies
    ↓
Engage Enemies
    ↓
Manage Health & Ammunition
    ↓
Use Pickups / Reload Weapon
    ↓
Defeat Enemies
    ↓
Complete Objective
    ↓
Clear the Area
```

---

# ✨ Features

## 🔫 FPS Weapon System

- First-person weapon setup
- Shooting system
- Projectile-based combat
- Weapon muzzle / firing effects
- Basic reload animation
- Ammunition management
- Ammo pickup system
- Ammo pickup sound
- Weapon aiming / iron-sight related setup
- Hit detection and damage handling

---

## 🎯 Dynamic Crosshair

The project includes a dynamic crosshair system designed to provide visual feedback during combat.

The crosshair changes according to the player's weapon state and movement, helping communicate weapon accuracy and combat state to the player.

This system was implemented using Unreal Engine's UMG/Blueprint workflow.

---

## 🔄 Reload System

A basic weapon reload system has been implemented.

The system includes:

- Reload animation
- Magazine/ammunition management
- Reload interaction
- Weapon state handling

The reload system is designed to provide the foundation for further weapon mechanics such as recoil, weapon switching, and multiple weapons.

---

## 📦 Ammo Pickup

Ammo pickups can be placed in the environment and collected by the player.

### Includes

- Pickup interaction
- Ammunition restoration
- Pickup sound
- Integration with the weapon ammunition system

This encourages the player to interact with the environment rather than relying on unlimited ammunition.

---

# 🤖 Enemy AI

One of the main focuses of the project is implementing AI-controlled enemies.

The current AI system includes:

### 👁️ Player Detection

Enemies can detect the player and react when the player enters their relevant detection area.

### 🏃 Enemy Following

Once the player is detected, the enemy can follow/chase the player.

### 💥 Reaction to Bullets

Enemies respond when they are hit by the player's weapon.

The combat interaction includes:

```text
Player Shoots
     ↓
Projectile / Hit Detection
     ↓
Enemy Receives Damage
     ↓
Enemy Reacts
     ↓
Hit Feedback / Effects
```

### 🔎 Enemy Scouting

The AI also includes basic scouting behavior, allowing enemies to search/observe their surrounding area rather than simply remaining stationary.

This provides the foundation for expanding the AI into more advanced states such as:

- Patrol
- Investigation
- Chase
- Attack
- Search
- Death

---

# 💥 Combat Feedback

Combat has been enhanced with visual and gameplay feedback.

Current combat feedback includes:

- Enemy hit effects
- Weapon firing effects
- Projectile hit detection
- Enemy reactions
- Damage interaction
- Sound feedback for pickups
- HUD feedback

The goal is to make combat feel more responsive rather than having enemies simply disappear when shot.

---

# ❤️ Health & Armor HUD

The project contains a gameplay HUD for displaying player survival information.

### HUD Components

- Health bar
- Armor bar
- Ammunition information
- Crosshair
- Gameplay information

The HUD is designed to provide important information without interrupting the player's first-person view.

---

# 🖥️ Gameplay UI

The project includes several UI/gameplay feedback systems, including:

- Health display
- Armor display
- Ammunition display
- Dynamic crosshair
- Kill feed
- Timer
- Objective-related UI
- Minimap

These systems are being integrated into a unified FPS HUD.

---

# ☠️ Kill Feed

A basic kill-feed system has been added to provide combat feedback to the player.

When an enemy is eliminated, the HUD can communicate the event to the player.

The kill feed provides the foundation for future features such as:

- Kill streaks
- Multi-kills
- Headshot notifications
- Enemy names
- Score notifications

---

# ⏱️ Timer System

A gameplay timer has been implemented as part of the objective-based gameplay.

The timer can be used to create pressure during combat and can later be connected to different game states such as:

- Mission completion
- Time-based objectives
- Game over
- Score calculation

---

# 🗺️ Minimap

The project also includes a live minimap system.

The minimap is intended to help the player understand their position within the playable environment and can be expanded to display:

- Player position
- Enemy locations
- Objective locations
- Important areas
- Pickup locations

---

# 🎯 Objective-Based Gameplay

The project is moving beyond simple shooting mechanics toward an objective-driven gameplay loop.

A basic objective has been implemented around **clearing an area of enemies**.

### Example Flow

```text
Objective Started
      ↓
Enter Combat Area
      ↓
Enemies Spawn / Become Active
      ↓
Fight Enemies
      ↓
Eliminate Remaining Enemies
      ↓
Area Cleared
      ↓
Objective Completed
```

This provides a foundation for building a larger mission system.

---

# 🧩 Technology Stack

| Technology                | Usage                           |
| ------------------------- | ------------------------------- |
| **Unreal Engine 5.7.4**   | Game engine                     |
| **Blueprints**            | Gameplay programming            |
| **UMG**                   | User interface                  |
| **Unreal AI Systems**     | Enemy behavior                  |
| **Animation System**      | Reload and character animations |
| **Particle / FX Systems** | Combat and hit effects          |
| **Audio System**          | Weapon and pickup feedback      |
| **First Person Template** | Initial player framework        |

---

# 🏗️ Development Approach

The project follows an iterative development approach.

Instead of implementing the entire game at once, individual gameplay systems are developed and tested separately.

### Development progression

```text
First Person Template
        ↓
Player & Camera
        ↓
Weapon / Shooting
        ↓
Health & Armor
        ↓
HUD
        ↓
Reload System
        ↓
Dynamic Crosshair
        ↓
Ammo Pickup
        ↓
Enemy AI
        ↓
Enemy Combat Reaction
        ↓
Hit Effects
        ↓
Kill Feed
        ↓
Timer
        ↓
Minimap
        ↓
Objectives
```

This approach makes it easier to identify bugs and understand how each Unreal Engine system interacts with the rest of the game.

---

# 🎮 Controls

| Action        | Input                |
| ------------- | -------------------- |
| Move Forward  | `W`                  |
| Move Left     | `A`                  |
| Move Backward | `S`                  |
| Move Right    | `D`                  |
| Look          | `Mouse`              |
| Fire          | `Left Mouse Button`  |
| Aim           | `Right Mouse Button` |
| Reload        | `R`                  |
| Jump          | `Space`              |

> **Note:** Controls may change as development continues.

---

# 🚀 Getting Started

## Requirements

Before opening the project, make sure you have:

- Windows PC
- Unreal Engine **5.7.4**
- Sufficient disk space for Unreal Engine project files
- A DirectX 12 compatible GPU recommended for development

## Clone the Repository

```bash
git clone https://github.com/YASHoder/First_Person-Shooter-Game-Unreal-Engine-5-.git
```

Then open the project directory.

## Open the Project

1. Install **Unreal Engine 5.7.4**.
2. Clone/download this repository.
3. Locate the `.uproject` file.
4. Right-click the `.uproject` file.
5. Select **Open with Unreal Engine 5.7.4**.
6. Allow Unreal Engine to generate any required project files.
7. Wait for shaders/assets to finish loading.
8. Open the playable level.
9. Press **Play**.

> Using the same Unreal Engine version used during development is recommended to minimize compatibility issues.

---

# 📁 Project Structure

The repository follows the standard Unreal Engine project structure.

```text
First_Person-Shooter-Game-Unreal-Engine-5-
│
├── Config/
│   └── Unreal Engine configuration files
│
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
│
├── *.uproject
│
└── README.md
```

> Exact content folders may evolve as new gameplay systems are added.

---

# 🧠 What I Learned

This project has been a practical way to learn Unreal Engine game development and Blueprint-based gameplay programming.

Through development, I worked with:

- Unreal Engine's First Person framework
- Blueprint scripting
- Character movement
- Weapon systems
- Projectile spawning
- Collision detection
- Damage systems
- Health and armor
- UMG widgets
- Dynamic HUD elements
- Animation systems
- Reload mechanics
- Pickup systems
- Enemy AI
- AI perception/reaction concepts
- Gameplay effects
- Timers
- Objectives
- Minimap systems
- Debugging Blueprint runtime errors
- Asset importing and setup
- Game-state-driven gameplay

The project has also helped me understand how independent systems such as weapons, AI, UI, animation, audio, and objectives can be connected into a complete gameplay loop.

---

# 🛠️ Current Development Status

| System                     | Status |
| -------------------------- | :----: |
| First Person Character     |    ✅   |
| Camera System              |    ✅   |
| Weapon System              |    ✅   |
| Shooting                   |    ✅   |
| Projectile / Hit Detection |    ✅   |
| Health System              |    ✅   |
| Armor HUD                  |    ✅   |
| Reload Animation           |    ✅   |
| Dynamic Crosshair          |    ✅   |
| Ammo Pickup                |    ✅   |
| Pickup Sound               |    ✅   |
| Enemy AI                   |    ✅   |
| Enemy Following            |    ✅   |
| Enemy Bullet Reaction      |    ✅   |
| Hit Effects                |    ✅   |
| Enemy Scouting             |    ✅   |
| Kill Feed                  |    ✅   |
| Timer                      |    ✅   |
| Minimap                    |    ✅   |
| Basic Objective System     |    ✅   |
| Advanced AI Combat         |   🔄   |
| Multiple Weapons           |   🔄   |
| Advanced Mission System    |   🔄   |
| Final Gameplay Polish      |   🔄   |

---

# 🔮 Future Improvements

The project is still under development. Planned improvements include:

### Gameplay

- Multiple weapons
- Weapon switching
- Improved recoil
- Improved weapon accuracy
- Advanced damage system
- Headshot system
- More enemy types
- Enemy attack behavior
- Improved enemy perception
- More objectives
- Mission progression
- Difficulty levels

### AI

- Patrol system
- Search/investigation behavior
- Cover system
- Combat states
- Group AI behavior
- Better navigation
- More advanced Behavior Tree logic

### UI

- Main menu
- Pause menu
- Settings menu
- Improved kill feed
- Objective tracker
- Improved minimap
- Damage indicators
- Better HUD animations

### Audio & Visuals

- Weapon sound variations
- Enemy sounds
- Footstep system
- Improved muzzle flashes
- Impact effects
- Environmental audio
- Camera shake
- Additional animation polish

---

# 📸 Screenshots & Gameplay

Screenshots and gameplay footage can be added here as the project continues to develop.

### Gameplay

> 🎥 Add gameplay video/GIF here.

### HUD

> 🖥️ Add HUD screenshot here.

### Enemy AI

> 🤖 Add enemy AI gameplay screenshot here.

### Combat

> 🔫 Add combat screenshot here.

---

# 🎓 Project Purpose

This project is primarily an **educational and portfolio game-development project** created to gain practical experience with Unreal Engine 5.

The focus is not only on creating a playable FPS, but also on understanding how different gameplay systems are designed, implemented, debugged, and connected together.

---

# 👨‍💻 Developer

**Yash Singh**

Game Developer | Unreal Engine 5 | Blueprint Development | Full Stack Developer

GitHub:
[https://github.com/YASHoder](https://github.com/YASHoder)

---

# 📌 Repository

**First Person Shooter — Unreal Engine 5**

[https://github.com/YASHoder/First_Person-Shooter-Game-Unreal-Engine-5-](https://github.com/YASHoder/First_Person-Shooter-Game-Unreal-Engine-5-)

---

## ⭐ Support

If you find this project interesting, consider giving the repository a ⭐ on GitHub.

Feedback, suggestions, and improvements are always welcome.

---

> **Built with Unreal Engine 5.7.4 🎮**
>
> *Learning game development one system at a time.*
