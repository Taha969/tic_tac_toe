# Tic-Tac-Toe Game (XO)

A classic Tic-Tac-Toe (Noughts and Crosses) game developed using Python and the Tkinter library for the graphical user interface (GUI).

# ✨ Features

 Graphical Interface: A simple and clean GUI for an engaging gameplay experience.

 Player Turns: Smooth alternation between players 'x' and 'o'.

   Win Detection: Automatically checks for all possible winning conditions (horizontal, vertical, and diagonal).

   Tie Handling: Accurately detects a tie game when all squares are filled without a winner.

   Random Start: A random player is selected to start each new game.

   Restart Button: Easily start a fresh game at any time.

🛠️ Prerequisites

    Python: Version 3.x or higher.

    Tkinter: The standard Python GUI library (usually included with a default Python installation).

🚀 How to Run

    Save the Code: Save the provided Python code into a single file (e.g., tictactoe.py).

    Execute: Open your terminal or command prompt, navigate to the directory where you saved the file, and run the following command:
    Bash

    python tictactoe.py

    Play: The game window will open. Click on the squares to make your moves.

🕹️ Gameplay Instructions

    Starting: The game randomly chooses either 'x' or 'o' to start first.

    Making a Move: Click on any empty square to place your symbol.

    Winning: The first player to get three of their symbols in a row (horizontally, vertically, or diagonally) wins! The winning line of squares will turn green.

    Ties: If all nine squares are filled and no player has won, the game is declared a tie. All squares will turn red.

    New Game: Click the "restart" button to clear the board and begin a new round.

⚙️ Key Code Functions (Overview)

Function	Description
next_turn(row, col)	Handles a player's move, places the symbol, and checks the game state.
check_winner()	Scans the board for any winning patterns or a tie condition.
check_empty_spaces()	Helper function to determine if any moves are left on the board.
start_new_game()	Resets the game board, selects a new random starting player, and updates the status label.
