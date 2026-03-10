
# 📘 Assignment: Hangman Game

## 🎯 Objective

Build the classic word-guessing game using Python strings, loops, and user input. You'll practice string manipulation, conditionals, random selection, and game logic.

## 📝 Tasks

### 🛠️ Game Setup and Word Selection

#### Description
Set up the game structure and implement a function to randomly select a word from a predefined list.

#### Requirements
Completed program should:

- Define a list of at least 10 words for the game
- Implement a function to randomly select a word
- Initialize game variables (guessed letters, attempts remaining, etc.)
- Display the initial hidden word state using underscores (e.g., `_ _ _ _`)

### 🛠️ Letter Guessing and Progress Tracking

#### Description
Implement the core guessing mechanism that accepts player input and updates the game state.

#### Requirements
Completed program should:

- Accept letter guesses from the user
- Check if the guessed letter is in the word
- Update the display to show revealed letters
- Track incorrect guesses and decrement attempts remaining
- Prevent duplicate guesses

### 🛠️ Game Win/Loss Logic

#### Description
Implement the logic to determine game outcomes and provide appropriate feedback.

#### Requirements
Completed program should:

- Detect when the word is completely guessed (win condition)
- Detect when attempts are exhausted (loss condition)
- Display the final hidden word or complete word
- Show win or lose messages with appropriate information
- Offer to play again
