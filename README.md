# 🐦 Flappy Bird Clone - Java Game Project

A fully playable desktop clone of the classic **Flappy Bird** game developed using **Java**, **Swing**, and **AWT** libraries. This project is ideal for students or beginners who want to learn Java GUI programming and basic game development logic.

---

## 📖 Introduction

This project is a clone of the popular **Flappy Bird** game, implemented using Java. The game involves a bird flying through a series of pipes without hitting them. It demonstrates object-oriented programming, GUI design, graphics rendering, and event-driven game control in Java.

---

## 💻 Technologies Used

- Java (JDK 8 or higher)
- Java Swing
- Java AWT
- Visual Studio Code (recommended IDE)

---

## ✨ Features

- Real-time gameplay using `javax.swing.Timer`
- Bird jump mechanics with gravity effect
- Dynamic top and bottom pipe generation
- Collision detection (bird and pipes or ground)
- Score tracking system
- Game over and restart capability (on rerun)

---

## 📁 Repository Structure
- Flappy-Bird-Clone/
- ├── Flappybird.java   (main game file with all logic and rendering)
- ├── flappybird.png    (bird sprite)
- ├── flappybirdbg.png  (game background)
- ├── toppipe.png       (top pipe image)
- ├── bottompipe.png    (bottom pipe image)
- ├── README.md         (complete project documentation)

---

## 🛠 Installation & Setup

### 📌 Requirements

- Java JDK 8 or later
- Visual Studio Code with **Extension Pack for Java**
  - Install: `Java Extension Pack` by Microsoft from VS Code Extensions
- Git (optional, for cloning)

### 📥 Steps to Run

1. **Clone or download** this repository:
```
git clone https://github.com/abdulhayykhan/Flappy-Bird-Clone.git
cd Flappy-Bird-Clone
```

2. **Open VS Code:**
   
Go to File → Open Folder and open the ```Flappy-Bird-Clone``` directory.

3. **Compile and Run:**

If using terminal inside VS Code:
```
javac Flappybird.java
java Flappybird
```

---

## 🎮 How to Play

- Press the **Spacebar** to flap upward.
- Avoid hitting the top and bottom pipes.
- You score a point for each set of pipes passed.
- Game ends on collision or hitting the ground.
- To play again, rerun the program.

---

## 🔍 Code Overview

### `Flappybird.java`

This file contains:

- `main()` method – game entry point
- Game loop – uses a Swing `Timer` to repaint the screen at fixed intervals
- `paint()` method – draws background, pipes, bird, and score
- Keyboard handling – spacebar event to make the bird "flap"
- Gravity simulation – bird falls over time unless it flaps
- Collision detection – checks if the bird hits a pipe or the ground

---

## 🖼 Assets Used

| File               | Description             |
|--------------------|-------------------------|
| `flappybird.png`   | The bird image          |
| `flappybirdbg.png` | The background          |
| `toppipe.png`      | Upper obstacle pipe     |
| `bottompipe.png`   | Lower obstacle pipe     |

> All image files must be placed in the root directory alongside `Flappybird.java`.

---

## 🐞 Known Issues

- No in-game restart button
- No sound effects
- Difficulty remains constant
- No pause or resume functionality

---

## 🚀 Future Enhancements

- [ ] Add in-game restart functionality
- [ ] Introduce sound effects (flap, score, collision)
- [ ] Increase difficulty over time (pipe speed/distance)
- [ ] Add menu screen with Start/Exit options
- [ ] High score saving

---

## 🕹 Gameplay Preview

<img src="gamepreview.gif" width="250" height="400"/>

---

## 📄 License

This project is licensed under the **MIT License**.

You are free to use, distribute, and modify the code with appropriate attribution.

---

## 👤 Author

**Abdul Hayy Khan**  

GitHub: [@abdulhayykhan](https://github.com/abdulhayykhan)

Linkeidn: [@abdul-hayy-khan](https://linkedin.com/in/abdul-hayy-khan)


> Made with ❤️ by Abdul Hayy Khan in Java after a lot of trial & error!
