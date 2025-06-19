
# 🎮 2048-Power Game

![Game Logo](image.png)

An enhanced version of the classic 2048 game with power-ups, customizable themes, and multiple music tracks.

---

## 📚 Table of Contents

- [✨ Features](#-features)
- [📦 Installation](#-installation)
- [🎮 Controls](#-controls)
- [🧠 Game Mechanics](#-game-mechanics)
- [⚡ Power-Ups](#-power-ups)
- [🔷 Special Tiles](#-special-tiles)
- [🎨 Themes](#-themes)
- [🎵 Music](#-music)
- [🛠 Development](#-development)
- [🪪 License](#-license)
- [📬 Contact](#-contact)
- [🖥 Class Portfolio](#-class-portfolio)

---

## ✨ Features

- 🧩 **Customizable Grid Size**: Play on grids from 4x4 to 10x10
- 🎨 **Multiple Themes**: Choose between Desert, Forest, and Space themes
- 🎶 **10 Music Tracks**: Various genres to suit your mood
- ⚡ **Power-Up System**: Special abilities to enhance gameplay
- 🔒 **Special Tiles**: Lock and bomb tiles add new challenges
- 📈 **Score Tracking**: Save and view your high scores

---

## 📦 Installation

1. Ensure you have [Processing](https://processing.org/) installed.
2. Clone this repository:
   ```bash
   git clone https://github.com/SarveshwarSenthilKumar/2048-Power.git
   ```
3. Open the source folder in Processing.
4. Click the **Run** button to launch the game.

---

## 🎮 Controls

- **Arrow Keys**: Move tiles (Up, Down, Left, Right)  
- **M**: Toggle music on/off  
- **T**: Cycle through music tracks  
- **1–0**: Select specific music tracks  
- **Mouse**: Click buttons in menus  

---

## 🧠 Game Mechanics

- Combine like-numbered tiles to double their value.
- Each move spawns a new tile (2, 4, or special tiles).
- Game ends when the grid fills with no valid moves.

### 🔧 Special Mechanics

- **Lock Tiles**: Stay in place for 8 moves, cannot be combined.
- **Bomb Tiles**: Destroy surrounding tiles when combined.

---

## ⚡ Power-Ups

Earn points to unlock unique powers:

| Power-Up      | Effect                                               | Cost                           |
|---------------|------------------------------------------------------|--------------------------------|
| ⚡ Lightning   | Clears board to a single tile                        | 25% of current score           |
| 444 Fours Only| Next 10 tiles will be 4s                              | 100 × grid size                |
| Undo          | Reverts last move                                    | 50 × grid size                 |
| 🔨 Hammer      | Destroys a random non-2 tile                         | 25 × grid size                 |
| 2× Double Mode| Next 10 combos give double points                    | 200 × grid size                |

---

## 🔷 Special Tiles

- **🔒 Lock Tiles**:  
  - Remain for 8 moves  
  - 5% chance to spawn  
  - Cannot be merged normally  

- **💣 Bomb Tiles**:  
  - Destroy surrounding tiles  
  - 2% chance to spawn (only with ≥4 empty spaces)  

---

## 🎨 Themes

Choose from three unique themes:

- 🏜 **Desert** – Warm earth tones  
- 🌲 **Forest** – Green nature palette  
- 🌌 **Space** – Cool cosmic tones  

---

## 🎵 Music

Includes 10 tracks from various genres:

1. Basic Lofi  
2. Baby - Justin Bieber ft. Ludacris  
3. Espresso - Sabrina Carpenter  
4. Party in the USA - Miley Cyrus  
5. What Makes You Beautiful - One Direction  
6. Shake It Off - Taylor Swift  
7. Wonderwall - Oasis (Developer's Pick)  
8. Careless Whisper - George Michael  
9. A.P.T. - Bruno Mars & Rose  
10. FEIN - Travis Scott  

---

## 🛠 Development

### 🔧 Technical Details

- Built with **Processing** (Java-based)
- Audio via **Minim library**
- Score tracking with **file I/O**
- Clean **object-oriented** architecture

### 🔑 Key Components

- **Grid System**: Dynamic 2D array logic, collision & movement handling  
- **UI System**: Multi-state screens, buttons, and theme customization  
- **Audio System**: Track switching, play/pause, and input binding  

---

## 🪪 License

This project is open source and available under the **MIT License**.

---

## 📬 Contact

**Developer:** Sarveshwar Senthil Kumar  
🌐 [Website](https://sarveshwarsenthilkumar.github.io)  
📧 sarveshwar313@gmail.com  
🐙 [GitHub](https://github.com/SarveshwarSenthilKumar)  
💼 [LinkedIn](https://linkedin.com/in/sarveshwarsenthilkumar)  

---

## 🖥 Class Portfolio

📁 [Introduction to Computer Science ICS Portfolio](https://sarveshwarsenthilkumar.github.io/IntroductionToComputerScienceICSPortfolio/)

---

> *2048-Power — A powerful twist on the puzzle classic!*
