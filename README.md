# 🔤 Java Hangman Game

A classic terminal-based Hangman game built with Java.  
Guess the hidden word one letter at a time — before the stickman is fully drawn!

---

## 🎮 Gameplay

- The game randomly selects a word from a `words.txt` file.
- You input letters to guess the word.
- Correct guesses reveal the letter in its position(s).
- Wrong guesses draw parts of the hangman.
- You lose after 6 incorrect attempts.

---

## 📦 Features

- ✅ Word loading from external text file
- ✅ Letter-by-letter guessing with feedback
- ✅ Hangman ASCII art that updates with each incorrect guess
- ✅ Input validation to prevent duplicate or invalid guesses
- ✅ Replay option after each game

---

## 🛠️ Technologies Used

- Java (JDK 8+)
- Standard input/output (console)
- File I/O

---

## 🚀 How to Run

### 1. Prerequisites

- Java installed (JDK 8 or later)
- An IDE like IntelliJ IDEA or any terminal
- `words.txt` file in the project directory (a list of possible words, one per line)

### 2. Clone the Repository

```bash
git clone https://github.com/harutyunyanazat29/java-hangman.git
cd java-hangman
