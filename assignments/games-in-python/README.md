
# 📘 Assignment: Hangman (Games in Python)

## 🎯 Objective

Build a command-line Hangman game in Python to practice string manipulation, loops, conditionals, and basic program flow.

## 📝 Tasks

### 🛠️ Core Hangman Implementation

#### Description
Implement the classic Hangman game using the provided starter code. The program should select a secret word and allow a player to guess letters until they either reveal the word or run out of attempts.

#### Requirements
Completed program should:

- Randomly select a word from a predefined list.
- Accept single-letter guesses and show current progress (for example: `_ p p _ e`).
- Track and display incorrect guesses remaining.
- Prevent repeated guessing of the same letter.
- End the game with a clear win or lose message.

### 🛠️ Optional Enhancements (Extra Credit)

#### Description
Add one or more enhancements to improve the game experience.

#### Suggestions

- Load words from an external file or `data.csv`.
- Add difficulty levels that change `max_attempts` or word length.
- Show a simple ASCII-art hangman that updates with each incorrect guess.
- Keep a high-score or number-of-wins counter saved to disk.

## 🧭 Starter Code

A minimal starter is provided at [assignments/games-in-python/starter-code.py](assignments/games-in-python/starter-code.py#L1-L200). Use it as the starting point and complete the TODOs.

## ▶️ Setup & Run

Run the assignment locally with Python 3:

```bash
python3 assignments/games-in-python/starter-code.py
```

No extra dependencies are required.

## ✅ Submission

- Submit your completed `starter-code.py` with the implemented logic.
- If you added external files (word lists, high-score storage), include them in the assignment folder and mention them in your submission notes.

## 📚 Resources

- Python `random` module for selecting words.
- String and list methods for tracking progress and guesses.

