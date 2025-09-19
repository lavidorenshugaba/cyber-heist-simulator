# 🔐 Cyber Heist Simulator

A simple **text-based Python adventure game** where you take on the role of a hacker infiltrating a digital fortress.
Your goal is to bypass four security layers without triggering the alarm.

---

## 🎮 Game Features (Original Version)

* **Four Security Layers**:

  1. **Firewall** → Guess a random port number (1–10).
  2. **Password System** → Crack the password chosen from a small list.
  3. **Security Logs** → Identify the suspicious log entry.
  4. **Encrypted Vault** → Solve a fixed math puzzle (5 × 8 – 10).
* **Attempts System**: You have a maximum of 3 wrong moves before the alarm triggers.
* **Win Condition**: Bypass all layers successfully.
* **Lose Condition**: Run out of attempts or trigger the alarm.

---

## 🖥️ Installation

1. Install Python 3.x
2. Clone this repository:

   ```bash
   git clone https://github.com/YourUsername/cyber-heist-simulator.git
   cd cyber-heist-simulator
   ```
3. Run the game:

   ```bash
   python cyber_heist_simulator.py
   ```

---

## 🕹️ Gameplay Overview

* Start with **3 attempts**.
* Each layer asks for input:

  * **Firewall**: guess the port.
  * **Password**: guess from a random list.
  * **Logs**: pick the suspicious entry.
  * **Vault**: solve the math puzzle.
* If you fail too many times → **Alarm triggered, Game Over**.
* If you pass all four layers → **Congratulations, you win!**

---

## 📂 Learning Objectives

This project demonstrates fundamental Python concepts:

* Variables and Data Types (`string`, `int`, `list`, `dict`, `bool`)
* Loops (`for`, `while`)
* Conditionals (`if`, `elif`, `else`)
* Functions (with return values)
* Error Handling (`try/except`)
* Randomization (`random` module)

---

## 🚀 Future Ideas (Not in this Version)

* Dynamic puzzles and randomized vault questions
* Difficulty levels (Easy/Medium/Hard)
* Scoring system with leaderboard
* Hints and countdown timers
* Colorful terminal output with `colorama`

---

## 👨‍💻 Author

Developed by **BIG\_LAVIDA**
