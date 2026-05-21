
# 📘 Assignment: Games in Python

## 🎯 Objective

Build a playable Hangman game in Python to practice string manipulation, loops, conditionals, and user interaction.

## 📝 Tasks

### 🛠️ Create the Game Loop

#### Description

Implement the main game loop that selects a hidden word, accepts letter guesses, and updates the displayed progress.

#### Requirements
Completed program should:

- Choose a random word from a predefined list
- Display the hidden word progress using underscores for unguessed letters
- Accept single-letter guesses from the player
- Reveal correct letters in the word as they are guessed

### 🛠️ Track Guesses and Game State

#### Description

Add logic to count incorrect guesses and determine whether the player wins or loses.

#### Requirements
Completed program should:

- Limit the number of incorrect guesses allowed
- Keep track of letters already guessed and avoid duplicate guesses
- End the game when the word is fully guessed or the player runs out of attempts
- Display a clear win message if the word is guessed, or a lose message with the correct word if attempts expire
