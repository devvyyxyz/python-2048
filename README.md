# 2048 Game

This is a Python implementation of the popular game 2048 using the tkinter module for the graphical interface.

# Prerequisites

Python 3.x
tkinter
#Usage

Clone this repository: git clone https://github.com/<username>/2048-game.git
Navigate to the cloned directory: cd 2048-game
Run the game: python main.py
# Game Controls

Use arrow keys to move tiles up, down, left, or right.
Press ESC to exit the game at any time.
# Code Explanation

The Board class creates the game board using a tkinter Frame widget. It initializes the board with a 4x4 grid of Label widgets, which are used to display the values of the tiles. The Board class also contains methods for compressing, merging, and randomizing the grid, as well as for painting the updated grid onto the game board.

The Game class creates a new instance of the Board class and listens for key presses from the user. When a key is pressed, the Game class performs the appropriate move and updates the grid on the game board. It also checks for win/loss conditions and displays a message box accordingly.

# License

This project is licensed under the MIT License. See the LICENSE file for details.
