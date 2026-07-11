
# 📘 Assignment: Games in Python

## 🎯 Objective

Build a fun Python game using loops, conditionals, and user input. You'll design game logic and make sure the player can win or lose based on clear rules.

## 📝 Tasks

### 🛠️ Build the Core Game Loop

#### Description
Create the core loop of a Hangman-style game where a player repeatedly guesses letters to uncover a hidden word.

#### Requirements
Completed program should:

- Randomly select a word from a predefined list
- Display current word progress using placeholders (for example: `_ _ _ _`)
- Accept and process one letter guess at a time

### 🛠️ Add Win/Loss Conditions

#### Description
Track incorrect guesses and finish the game when the player wins or runs out of attempts.

#### Requirements
Completed program should:

- Decrease remaining attempts only for incorrect guesses
- End the game with a win message when the full word is guessed
- End the game with a lose message when attempts reach zero
