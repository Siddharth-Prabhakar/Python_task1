# 🕹️ Hangman - Text-Based Python Game

A simple console-based Hangman game built with Python. The player must guess a randomly chosen word one letter at a time, with a maximum of 6 incorrect guesses allowed.

---

## 🎯 Game Objective

Guess the hidden word by entering one letter at a time. you win by guessing the full word before running out of attempts.

---

## 📋 Features

- Random word selection from a list of 5 predefined words
- Tracks and displays guessed letters
- Limits incorrect guesses to 6
- Prevents repeated or invalid guesses
- Console-based interaction only (no GUI or audio)

---

## 🚀 How to Run

1. Make sure Python is installed on your system.
2. Save the script as `hangman.py`.
3. Open a terminal or command prompt.
4. Run the game using:

```bash
python hangman.py
```

---

## 🖥️ Sample Output

```
Word: ______
Incorrect guesses left: 6
Guessed letters: 
Guess a letter: w
Sorry, 'w' is not in the word.

Word: ______
Incorrect guesses left: 5
Guessed letters: w
Guess a letter: a
Sorry, 'a' is not in the word.

Word: ______
Incorrect guesses left: 4
Guessed letters: a, w
Guess a letter: e
Sorry, 'e' is not in the word.

Word: ______
Incorrect guesses left: 3
Guessed letters: a, e, w
Guess a letter: r
Sorry, 'r' is not in the word.

Word: ______
Incorrect guesses left: 2
Guessed letters: a, e, r, w
Guess a letter: e
You've already guessed that letter.

Word: ______
Incorrect guesses left: 2
Guessed letters: a, e, r, w
Guess a letter: g
Sorry, 'g' is not in the word.

Word: ______
Incorrect guesses left: 1
Guessed letters: a, e, g, r, w
Guess a letter: c
Sorry, 'c' is not in the word.

Game over! You ran out of guesses.
The word was: kotlin
```

---

## 👤 Author

Created by siddharth Prabhakar 
