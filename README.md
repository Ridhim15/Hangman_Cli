# Hangman CLI Game

This is a command-line implementation of the classic Hangman game in Python. The game allows a user
to guess letters of a randomly chosen word and provides hints if requested.

## Features

- Play Hangman in the command line.
- Provides hints to the user after a certain number of incorrect guesses.
- Displays the hangman stages as the game progresses.
- Keeps track of the user's guesses.

## Requirements

- Python 3.x

## Installation

1. Clone the repository:

   ```sh
   git clone https://github.com/ridhimg15/Hangman_CLI.git
   cd Hangman_CLI
   ```

2. Install the required libraries (if any):
   ```sh
   pip install -r requirements.txt
   ```

## Usage

Run the game using the following command:

```sh
python main.py
```

## Game Rules

- A random word is chosen from a predefined list.
- The user guesses letters one at a time.
- If the guessed letter is in the word, it is revealed in the correct positions.
- If the guessed letter is not in the word, the user loses a life.
- The user can request a hint after a certain number of incorrect guesses.
- The game continues until the user either guesses the word or runs out of lives.

## Code Overview

### Main Game Loop

The main game loop is implemented in the `main.py` file. It handles user input, game logic, and
displaying the hangman stages.

### Hint Function

The hint function provides hints to the user based on the current game state. It is called if the
user requests a hint.

### Hangman Stages

The hangman stages are displayed as the user makes incorrect guesses.

## Example Output

```
Hint function can be called
Press any key if you want hint
Press 'n' if you want to continue without hint

Guess a letter
a
Your chosen letter: a is correct
__ a __ __ __

Guess a letter
```

