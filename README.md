# 🔑 Password Guess Game

A fun **Python word-guessing game** with a beautiful, modern **Tkinter GUI** styled by **ttkbootstrap**. Pick your difficulty, guess the hidden word, and get hints — it’s like a mix between **Hangman** and **Wordle**!

---

## 📌 Overview

What it does:

- Pick a difficulty: **Easy**, **Medium**, or **Hard**
- The game picks a secret word from that level’s word list
- You guess the word by typing and submitting
- The game gives you hints for each letter’s correct position
- You win if you guess the word within your allowed attempts!

---

## 🚀 Key Features

✅ **Three Difficulty Levels**
- Easy: 10 tries
- Medium: 8 tries
- Hard: 6 tries

✅ **Dynamic Hints**
- Shows matching letters in the correct position after each guess.

✅ **Modern Look**
- Built with **ttkbootstrap** for a sleek, themed GUI.

✅ **Play Again**
- Restart anytime with a single click — no need to relaunch.

✅ **Beginner-Friendly**
- Clear Python code that’s easy to read and extend.

---

## ⚙️ How It Works

- A random word is picked from the chosen difficulty’s word list.
- The player types a guess and submits it.
- The game checks the guess:
  - ✅ If correct: you win!
  - ❌ If wrong: shows a hint with matching letters and updates attempts.
- The game ends when you guess correctly or run out of tries.
- A **Play Again** button lets you start over instantly.

---

## 🧰 Tech Stack

- **Python 3**
- **Tkinter**
- **ttkbootstrap** (`pip install ttkbootstrap`)

---

## 📸 Screenshots

| Easy level | Medium level | Hard level |
|-------------------|----------------------|--------------------|
| <img width="555" height="483" alt="Select Difficulty" src="https://github.com/user-attachments/assets/1f4f9a11-2998-46e1-844a-5ca0df564ffe" /> | <img width="550" height="483" alt="Guessing in Progress" src="https://github.com/user-attachments/assets/df7a360e-5525-48d6-b60b-57073cd17d6b" /> | <img width="555" height="486" alt="Game Over" src="https://github.com/user-attachments/assets/25767025-6cd3-4ae6-bfb4-6abcccb90f4b" /> |

---

## 🚀 How to Run

1️⃣ **Clone this repo**

```bash
git clone https://github.com/Salman-Dev262/password-guess-game.git
cd password-guess-game
```
## Install dependencies
```
pip install ttkbootstrap
```

## Run the game
```
python password_guess_game.py
```
## ✅ Next Steps
💡 Ideas to Extend

Add word categories (Animals, Countries, Fruits, etc.)

Display a list of previously guessed words

Add keyboard shortcuts (press Enter to submit)

Add a dark mode toggle

Save scores or implement a leaderboard

## 🙌 Author
Created by Salman Ali
📌 A simple project to practice Python GUIs and modern UI styling with ttkbootstrap.

Feel free to ⭐️ star, fork, and share — Happy Coding!
