# 🥦 Veggie Vanguard: The Root of All Courage 🥕

![Unity](https://img.shields.io/badge/Unity-100000?style=for-the-badge&logo=unity&logoColor=white)
![C#](https://img.shields.io/badge/C%23-239120?style=for-the-badge&logo=c-sharp&logoColor=white)
![GameDev](https://img.shields.io/badge/Game_Development-blue?style=for-the-badge)

**Veggie Vanguard** is a 3D turn-based RPG developed to showcase advanced game state management, engaging combat mechanics, and dynamic scene transitions. Take control of a brave party of vegetable heroes as they defend their peaceful village from the spreading corruption of the Rot King and his minions!

---

## 🚀 The Problem We Solve

Many beginner RPG projects struggle with maintaining persistent game states across different scenes, often resulting in reset progress or clunky transitions. 

**Veggie Vanguard** solves this by implementing a robust, decoupled `GameManager` architecture that flawlessly remembers player victories and alters the game world dynamically. Defeating the final boss permanently changes the village environment from a state of panic to a peaceful, portal-free hub, demonstrating strong understanding of persistent data flow in game development.

---

## ✨ Key Features

* 🗺️ **Free-Roam Village Hub:** Explore the village in real-time, interact with NPCs, and discover event-triggered portals that lead to battle zones.
* ⚔️ **Classic Turn-Based Combat:** Strategic battle loop featuring standard attacks, elemental weaknesses, and distinct enemy behaviors (Rot Sprout, Rot Sentinel, and Rot King).
* 🎥 **Dynamic Combat Cameras:** Custom coroutine-based camera system that focuses on action, including close-ups for ultimate skills and standard battle views.
* 🛡️ **Advanced Unit Mechanics:** Deep combat system including health and shield management, critical hit calculations, and item usage (Healing and Reviving).
* 💾 **Persistent Game State (DontDestroyOnLoad):** A singleton Game Manager that carries data between the Village and Battle scenes, ensuring the world reacts to your progression.
* 🖥️ **Dynamic Battle UI:** Custom-built interface featuring boss health bars, floating damage numbers, and interactive action menus.

---

## 🛠️ Tech Stack

### Game Engine
* **Engine:** Unity 3D
* **Language:** C#
* **Navigation:** Unity NavMesh (for dynamic unit movement during battles)

### UI & Visuals
* **Interface:** Unity Canvas & TextMeshPro
* **Animations:** Unity Animator (State Machines for Idle, Attack, Cast, Die)
* **VFX:** Unity Particle System (Magic attacks, weapon trails, hit effects)

---

## 📸 Screenshots
*(Note: Upload your UI screenshots to an `assets` folder in your GitHub repo to display them here)*

| Village Exploration | Enemy Encounter | Boss Battle | Ai Npc |
| :---: | :---: | :---: | :---: |
| <img src="assets/village.jpeg" width="200"/> | <img src="assets/enemies.jpeg" width="200"/> | <img src="assets/boss.jpeg" width="200"/> | <img src="assets/victory.jpeg" width="200"/> |

---

## 📥 Try the Prototype (Playable Build)

> **⚠️ Academic Project Disclaimer:** > *Veggie Vanguard is a game development project for academic purposes at the Faculty of Computer Science and Information Technology (FSKTM), UTHM. This is a prototype build and **not an official commercial release**.*

If you would like to test the game mechanics, you can download the prototype build:

**Step 1: Download the Game**
* Go to the [Releases page](../../releases/) of this repository.
* Download the `VeggieVanguard-Prototype-v1.0.zip` file to your computer.

**Step 2: Extract & Play**
* Unzip the downloaded folder to your preferred location.
* Open the folder and double-click `VeggieVanguard.exe` to launch the game.

**Step 3: Explore the Mechanics**
* Start a new game, walk into the Red Portal when the earthquake starts, and test your skills against the Rot King!
