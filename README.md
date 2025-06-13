# Java Games Collection 🎮

This repository contains two Java-based games:
1. **MatchCard Memory Game**
2. **Flappy Bird Clone**

Each game demonstrates GUI programming, object-oriented design, and event handling in Java.

---

## 🔹 1. MatchCard Memory Game

### 🧠 Description
A classic memory game where players flip cards and try to find matching pairs.

### 🧩 Game Logic
- A grid of cards is displayed face down.
- Each card has a matching pair.
- Clicking a card reveals its image.
- If two consecutively flipped cards match, they remain face up.
- If not, both are flipped back after a short delay.
- The game ends when all pairs are matched.

### 💡 Features
- Timer to track how fast the game is completed.
- Moves counter.
- Shuffle logic using `Collections.shuffle()` on card list.
- GUI implemented with **Swing**.

---

## 🔹 2. Flappy Bird (Java Clone)

### 🐦 Description
A simple clone of the popular Flappy Bird game developed using Java.

### 🚀 Game Logic
- The bird falls due to gravity and jumps when the spacebar is pressed.
- Pipes continuously move from right to left.
- Collision detection with pipes or ground ends the game.
- Score increases each time the bird passes a set of pipes.

### 💡 Features
- Physics-based vertical movement.
- Randomized gap heights between pipes.
- Basic sound effects.
- GUI with **Java AWT** and **Swing**.

---

## 🖼️ Screenshots

### MatchCard Game
![image](https://github.com/user-attachments/assets/91da12da-e47c-40e0-90e2-60e639dda6b9)


### Flappy Bird Game
![image](https://github.com/user-attachments/assets/fe0f4a97-6977-4499-91f4-c3b52c24a1cd)


> 📁 Store the screenshots in an `images` folder inside the repo.

---


---

## 🛠️ How to Run

Make sure you have Java installed.

### Run from terminal:
```bash
javac MatchCardGame.java
java MatchCardGame
