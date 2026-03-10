# 🥦 Veggie Vanguard: The Root of All Courage 🥕

![Unity](https://img.shields.io/badge/Unity-100000?style=for-the-badge&logo=unity&logoColor=white)
![C#](https://img.shields.io/badge/C%23-239120?style=for-the-badge&logo=c-sharp&logoColor=white)
![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=for-the-badge&logo=openai&logoColor=white)
![GameDev](https://img.shields.io/badge/Game_Development-blue?style=for-the-badge)

**Veggie Vanguard** is a 3D turn-based RPG developed to showcase advanced game state management, engaging combat mechanics, and dynamic AI interactions. Take control of a brave party of vegetable heroes as they defend their peaceful village from the spreading corruption of the Rot King and his minions! 

---

## 🚀 The Problem We Solve

Many beginner RPG projects struggle with maintaining persistent game states across different scenes, and traditional NPC dialogue trees often feel static and repetitive. 

**Veggie Vanguard** solves this by implementing a robust, decoupled `GameManager` architecture that flawlessly remembers player victories and alters the game world dynamically. Furthermore, the game replaces static dialogue trees with **Generative AI NPCs**, allowing players to use their actual voice to have dynamic, context-aware conversations with villagers, demonstrating a strong understanding of persistent data flow and API integration.

---

## ✨ Key Features

* 🎙️ **Voice-Activated AI NPCs:** Engage in dynamic, real-time conversations with village NPCs. Powered by OpenAI's API and Speech-to-Text (STT) integration, players can speak directly into their microphones for an immersive, unscripted roleplay experience.
* 🗺️ **Free-Roam Village Hub:** Explore the village in real-time, talk to the AI villagers, and discover event-triggered portals that lead to battle zones.
* ⚔️ **Classic Turn-Based Combat:** Strategic battle loop featuring standard attacks, elemental weaknesses, and distinct enemy behaviors (Rot Sprout, Rot Sentinel, and Rot King).
* 🎥 **Dynamic Combat Cameras:** Custom coroutine-based camera system that focuses on action, including close-ups for ultimate skills and standard battle views.
* 🛡️ **Advanced Unit Mechanics:** Deep combat system including health and shield management, critical hit calculations, and item usage (Healing and Reviving).
* 💾 **Persistent Game State (DontDestroyOnLoad):** A singleton Game Manager that carries data between the Village and Battle scenes, ensuring the world reacts to your progression.
* 🖥️ **Dynamic Battle UI:** Custom-built interface featuring boss health bars, floating damage numbers, and interactive action menus.

---

## 🛠️ Tech Stack

### Game Engine & AI
* **Engine:** Unity 3D
* **Language:** C#
* **AI Integration:** OpenAI API (Generative text for dynamic NPC dialogue)
* **Voice Input:** Speech-to-Text (STT) audio processing

### UI & Visuals
* **Interface:** Unity Canvas & TextMeshPro
* **Animations:** Unity Animator (State Machines for Idle, Attack, Cast, Die)
* **VFX:** Unity Particle System (Magic attacks, weapon trails, hit effects)
* **Navigation:** Unity NavMesh (for dynamic unit movement during battles)

---

## 📸 Screenshots

| Village Exploration | Enemy Encounter | Boss Battle | Ai Interact NPC |
| :---: | :---: | :---: | :---: |
| <img src="assets/Village Exploration.png" width="200"/> | <img src="assets/Enemy encounter.png" width="200"/> | <img src="assets/boss battle.png" width="200"/> | <img src="assets/Ai interact npc.png" width="200"/> |

---

## 📥 Try the Prototype (Playable Build)

> **⚠️ Academic Project Disclaimer:** > *Veggie Vanguard is my game development project within 4 months for academic purposes at the Faculty of Computer Science and Information Technology (FSKTM), UTHM. This is a prototype build and **not an official commercial release**.*

If you would like to test the game mechanics, you can download the prototype build:

**Step 1: Download the Game**
* Go to the [releases page](../../releases/) of this repository.
* Copy the google drive link and download the `VeggieVanguard-Prototype-v1.0.zip` file to your computer.

**Step 2: Extract & Play**
* Unzip the downloaded folder to your preferred location.
* Open the folder and double-click `VeggieVanguard.exe` to launch the game.

**Step 3: Explore the Mechanics**
* Start a new game, use your microphone to talk to the villagers, walk into the Red Portal when the earthquake starts, and test your skills against the Rot King!
