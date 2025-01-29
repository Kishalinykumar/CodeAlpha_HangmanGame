# CodeAlpha_HangmanGame
Hangman game developed using python for python programming internship at CodeAlpha (Task1)

# Hangman Game

## Overview
This is a simple command-line Hangman game implemented in Python. The game selects a random word from a predefined list, and the player must guess the word one letter at a time. The player has a limited number of attempts to guess the word correctly.

## How to Play
1. The game randomly selects a word from a list of words.
2. The player guesses one letter at a time.
3. If the guessed letter is in the word, it is revealed in the correct positions.
4. If the guessed letter is incorrect, the player loses an attempt.
5. The player has a maximum of 6 incorrect attempts before the game is over.
6. The game ends when the player either guesses the entire word or runs out of attempts.

## Prerequisites
- Python 3.x installed on your system

## Running the Game
1. Save the script as `hangman.py`.
2. Open a terminal or command prompt.
3. Navigate to the directory where `hangman.py` is located.
4. Run the script using the command:
   ```bash
   python hangman.py
   ```

## Features
- Random word selection from a predefined list.
- Tracks guessed letters to prevent duplicate guesses.
- Displays the word with guessed letters revealed.
- Provides feedback on correct and incorrect guesses.
- Ends the game when the word is guessed or attempts run out.

## Example Gameplay
```
Welcome to Hangman!
Guess the word, one letter at a time.
The word has 7 letters.
_ _ _ _ _ _ _

Enter a letter: a
Wrong guess! You have 5 attempts left.
_ _ _ _ _ _ _

Enter a letter: o
Good job! 'o' is in the word.
_ o _ _ _ _ _

... (continues until the game ends)

Congratulations! You guessed the word: hangman
```

## License
This project is open-source and free to use.

## Author
Created by [Kishaliny K]


