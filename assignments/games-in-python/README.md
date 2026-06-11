
# 📘 Assignment: Hangman Game

## 🎯 Objective

Build a classic Hangman word-guessing game to practice Python strings, loops, conditionals, and user input.

## 📝 Tasks

### 🛠️ Word Selection and Setup

#### Description
Create a predefined list of words and choose one word at random for the player to guess.

#### Requirements
Completed program should:

- Define a list of possible words inside the program
- Randomly select one word for the current game
- Initialize game state variables to track guesses, display progress, and count attempts

### 🛠️ Guess Processing and Progress Display

#### Description
Accept letter guesses, update the hidden word display, and show which letters have been guessed.

#### Requirements
Completed program should:

- Prompt the player to enter one letter at a time
- Reveal correctly guessed letters in the word display (e.g. `_ a _ g _ a _`)
- Track letters already guessed and prevent duplicate guesses
- Update the display after each valid guess

### 🛠️ Game End Conditions and User Feedback

#### Description
Check for win/loss conditions and notify the player when the game ends.

#### Requirements
Completed program should:

- Track a limited number of incorrect guesses (attempts remaining)
- End the game when the word is fully guessed or attempts run out
- Print a win message if the player guesses the word
- Print a lose message and reveal the word if attempts are exhausted

