# 🐍 Snake Game

A classic **Snake Game** implemented in C++ — works on **Windows & Linux & Mac**!

## Table of Contents
- [Features](#Features)
- [Usage](#usage)
- [Contributors](#Contributors)
- [License](#license)

## ✨ Features
- 🔮 **Cross-Platform Compatibility** (Windows & Linux & Mac)
- 🛠️ **Adjustable Difficulty Levels** (Easy, Medium, Hard)
- ⭐ **Smooth Gameplay** with responsive controls
- ⚙️ **Optimized Code** using Object-Oriented Programming (OOP) principles

## 🔄 Gameplay Mechanics
- Control the snake using **W, A, S, D** keys.
- Eat the food (🍓) to grow your tail and increase your score!
- Avoid **colliding** with the walls or yourself.
- **Game Over** when you hit a wall or your own body.
- **Press 'Esc'** to quit the game anytime.

## 📚 Installation & Run
### 1️⃣ Clone the Repository
```sh
git clone https://github.com/yourusername/SnakeGame.git
cd SnakeGame
```

### 2️⃣ Compile & Run
#### 🌟 Windows
```sh
g++ snake_game.cpp -o snake_game.exe -static-libstdc++ -static-libgcc
.\snake_game.exe
```

#### 🌟 Linux
```sh
g++ snake_game.cpp -o snake_game
./snake_game
```

## 🎯 Game Controls
| Key | Action |
|-----|--------|
| **W** | Move Up |
| **A** | Move Left |
| **S** | Move Down |
| **D** | Move Right |
| **ESC** | Quit Game |

## ⚖️ Difficulty Levels
Upon starting, choose a difficulty level:
- **1 - Easy (🏆 60ms delay)**
- **2 - Medium (🌟 35ms delay)**
- **3 - Hard (🥇 15ms delay)**

## ⚙️ Technical Details
- Uses **vector** for snake body storage.
- **Platform-Specific Input Handling:**
  - **Windows:** Uses `_kbhit()` and `_getch()`.
  - **Linux:** Uses `termios` and `select()`.
- **Randomized food placement** to avoid spawning inside the snake.

## 🛠️ Future Enhancements
- 🌈 Custom themes & colors
- 🌟 Score leaderboard
- 🧠 Obstacles & Power-ups
- ⭐ Multi-level game modes

## 💪 Contribution
1. Fork the repo.
2. Create a new branch (`feature-xyz`).
3. Commit changes (`git commit -m "Added xyz feature"`).
4. Push (`git push origin feature-xyz`).
5. Open a Pull Request!

## 🌟 Show Some Love
Give this project a ⭐ if you like it!

## 👥 Contributors
- [@AaryanModi](https://github.com/Aaryan-Modi)
- [@AdityaDave](https://github.com/Aditya-Dave503)
- [@JayLimbasiya](https://github.com/Jay0001-debug)
- [@RudraBhatt](https://github.com/RudraBhat)
  
---
Enjoy the game! 🚀

