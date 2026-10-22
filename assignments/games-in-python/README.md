# 📘 Assignment: Hangman Game Challenge

## 🎯 Objective

Build a word-guessing game in Python while practicing strings, loops, conditionals, and user input. You will reveal a hidden word one letter at a time and try to solve it before your incorrect guesses run out.

## 📝 Tasks

### 🛠️ Set Up the Game

#### Description
Create the word list and initialize a new Hangman game by choosing a hidden word at random.

#### Requirements
Completed program should:

- Store at least five words in a predefined list.
- Randomly select one word from the list for each game.
- Keep the selected word hidden from the player at the start.


### 🛠️ Accept Guesses and Show Progress

#### Description
Let the player guess letters and show which letters in the hidden word have been found.

#### Requirements
Completed program should:

- Prompt the player to enter one letter per turn.
- Display each unrevealed letter as an underscore and each correctly guessed letter in its matching position.
- Reduce the number of remaining attempts when the guessed letter is not in the word.
- Show how many incorrect guesses remain, starting with six.


### 🛠️ End the Game

#### Description
Finish the game when the player reveals the whole word or runs out of incorrect guesses.

#### Requirements
Completed program should:

- Stop accepting guesses when the word is fully revealed or no attempts remain.
- Display a win message when the player guesses the word.
- Display a lose message and reveal the hidden word when the player runs out of attempts.
