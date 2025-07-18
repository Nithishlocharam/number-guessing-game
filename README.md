Number Guessing Game

The **Number Guessing Game** is a simple Python console application that challenges users to guess a randomly selected number within a user-defined range. It encourages logical thinking and problem-solving by promoting the use of a binary search strategy to identify the number efficiently within a limited number of attempts.

---

## 📌 Features

- User-defined lower and upper bounds
- Random number generation
- 7 attempts to guess the correct number
- Real-time feedback: "Too high" or "Too low"
- Win and loss messages
- Simple and interactive command-line interface

---

## 🛠️ How It Works

1. The player enters a lower and upper bound.
2. The game randomly selects a number within that range.
3. The player has **7 chances** to guess the number.
4. After each guess, feedback is given:
   - Too high → try a smaller number
   - Too low → try a bigger number
5. If guessed correctly, the player is congratulated.
6. If not, the correct number is displayed after 7 attempts.

---

## 💻 Getting Started

### Requirements

- Python 3.x

### Run the Game

```bash
python guessing_game.py
