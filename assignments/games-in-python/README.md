# 📘 Assignment: Hangman Game

## 🎯 Objective

Build a playable Hangman game in Python while practicing string handling, loops, and conditionals. You will manage game state, validate guesses, and give clear feedback to the player.

## 📝 Tasks

### 🛠️ Create the Core Game Loop

#### Description
Implement the main Hangman gameplay: choose a secret word, accept letter guesses, and update progress until the game ends.

#### Requirements
Completed program should:

- Randomly select a word from a predefined list.
- Display the current word progress using underscores (e.g., `_ _ _ _`).
- Accept single-letter guesses and reveal matching letters.
- Track remaining incorrect guesses and end the game when guesses run out or the word is solved.


### 🛠️ Improve Player Feedback

#### Description
Add clear prompts and end-of-game messages so the player always knows what to do and how they performed.

#### Requirements
Completed program should:

- Reject invalid input (empty input or more than one character).
- Inform the player when a guess was already attempted.
- Show a win message when the word is guessed.
- Show a loss message and reveal the secret word when guesses are exhausted.
