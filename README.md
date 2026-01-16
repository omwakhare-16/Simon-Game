# 🎮 Simon Game

A simple **Simon Game** built using **HTML, CSS, JavaScript, and jQuery**.  
The game tests your memory by generating a sequence of colors that the player must repeat correctly.

---

## 🚀 How the Game Works

1. Press **any key** to start the game.
2. The game will highlight a random color.
3. The player must click the colors in the **same order**.
4. Each successful round increases the **level** and adds a new color to the sequence.
5. If the player clicks a wrong color, the game ends.
6. Press any key to **restart** after game over.

---

## 🧠 Game Logic Overview

- `gamePattern` stores the randomly generated color sequence.
- `userClickedPattern` stores the user’s input sequence.
- After every click, the game checks:
  - If the latest user input matches the game pattern.
  - If the entire sequence is completed, the game moves to the next level.
- On a wrong answer:
  - A sound is played
  - Screen flashes
  - Game resets

---

## 🛠️ Technologies Used

- HTML
- CSS
- JavaScript
- jQuery

---

## 📁 Project Structure
Simon-Game/
│
├── index.html
├── styles.css
├── index.js
├── sounds/
│ ├── red.mp3
│ ├── blue.mp3
│ ├── green.mp3
│ ├── yellow.mp3
│ └── wrong.mp3
└── README.md

---

## ▶️ How to Run the Project

1. Clone the repository or download the ZIP.
2. Open `index.html` in your browser.
3. Press any key to start playing.

---

## 📌 Features

- Dynamic level progression
- Sound and animation feedback
- Keyboard-based start
- Game over animation and restart functionality

---

## 🎯 Learning Outcomes

- DOM manipulation using jQuery
- Event handling (click & keydown)
- Arrays and game state management
- Debugging common JavaScript mistakes

---

## 🙌 Acknowledgements

Inspired by the classic **Simon Game** and commonly used in beginner JavaScript learning projects.

---

## 📄 License

This project is open-source and free to use for learning purposes.

