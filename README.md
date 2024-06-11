# X_O_Game

**Tic Tac Toe Game**

Welcome to the classic Tic Tac Toe game implemented in Python. This is a command-line based game where two players, X and O, take turns marking the spaces in a 3×3 grid. The player who succeeds in placing three of their marks in a horizontal, vertical, or diagonal row wins the game.

# Features
* Simple command-line interface: Play Tic Tac Toe in your terminal.
* Two-player mode: Two human players can play against each other.
* Real-time game board update: The game board updates in real-time after each move.
* Win detection: The game detects and announces the winner once the winning condition is met.

# How to Play
* Run the script: Execute the script in a Python environment.
* Follow the prompts: Players will be prompted to enter their moves.
* Take turns: Players X and O will take turns to enter their move (0-8) corresponding to the grid position.
* Win the game: The first player to align three of their marks horizontally, vertically, or diagonally wins the game.

# Game Board Layout

The game board positions are numbered as follows:
0 | 1 | 2
--|---|---
3 | 4 | 5
--|---|---
6 | 7 | 8

Example Gameplay: 

Welcome to Tic Tac Toe
0 | 1 | 2
--|---|---
3 | 4 | 5
--|---|---
6 | 7 | 8

X's Chance

Please enter a value: 0
X | 1 | 2
--|---|---
3 | 4 | 5
--|---|---
6 | 7 | 8

O's Chance

Please enter a value: 4
X | 1 | 2
--|---|---
3 | O | 5
--|---|---
6 | 7 | 8

# Code Explanation

**Functions**
* sum(a, b, c): Returns the sum of three numbers. Used to check winning conditions.
* printBoard(xState, zState): Prints the current state of the game board.
* checkWin(xState, zState): Checks if there's a winning condition for either player. Returns 1 if X wins, 0 if O wins, and -1 if the game continues.

**Main Loop**
The main loop runs the game, alternating turns between players X and O. It prompts the current player to enter a move, updates the game state, prints the updated game board, and checks for a winner. The game loop terminates when a player wins or the board is full.

**Requirements**
Python 3.x

**How to Run**
* Make sure you have Python 3 installed on your system.
* Download or clone this repository.
* Navigate to the directory containing the script.
* Run the script using the command: python game_X_and_O.py
* Enjoy playing Tic Tac Toe!
