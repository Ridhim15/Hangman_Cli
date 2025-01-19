# Rock Paper Scissors Game

This is a simple Rock Paper Scissors game implemented in Python. The game allows a user to play
against the computer and keeps track of the scores.

## Features

- Play Rock Paper Scissors against the computer.
- Keeps track of the scores.
- Provides hints to the user.
- Displays the game stages.

## Requirements

- Python 3.x
- `colorama` library for colored text output.

## Installation

1. Clone the repository:

   ```sh
   git clone https://github.com/yourusername/Rock_Paper_Scissors.git
   cd Rock_Paper_Scissors
   ```

2. Install the required libraries:
   ```sh
   pip install -r requirements.txt
   ```

## Usage

Run the game using the following command:

```sh
python main.py
```

## Game Rules

- The user and the computer choose between Rock, Paper, and Scissors.
- The winner is determined based on the following rules:
  - Rock beats Scissors.
  - Scissors beat Paper.
  - Paper beats Rock.
- The game continues until the user decides to stop.

## Code Overview

### Main Game Loop

The main game loop is implemented in the `main.py` file. It handles user input, game logic, and
score tracking.

### Hint Function

The hint function provides hints to the user based on the current game state. It is called if the
user requests a hint.

### Score Board

The score board displays the current scores of the user and the computer.

## Example Output

```
You chose Rock
Computer chose Scissors
You win!

Score Board: Traveller's Score: 1 Computer's Score: 0
```

