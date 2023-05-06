# python-2048

This code is a Python implementation of the popular game "2048". It is a GUI-based game created using the Tkinter library. 

The program starts by importing required libraries such as "tkinter" and "random". It then defines two dictionaries called "bg_color" and "color" which store the color codes for the background and text of the game cells. 

The program defines a "Board" class which initializes a 4x4 grid and sets up the game window using the Tkinter library. It also defines several methods that operate on the grid, including a "compressGrid" method which compresses the grid by removing empty cells, a "mergeGrid" method which merges adjacent cells of the same value, a "random_cell" method which adds a random cell to the grid, and a "paintGrid" method which updates the visual representation of the grid.

The "Game" class is then defined, which initializes the game and starts the game loop. The "start" method initializes the game board by adding two random cells to the grid. It then binds the arrow keys to the "link_keys" method which handles key presses during the game. 

The "link_keys" method takes the pressed key as input and uses it to determine which action to take on the grid. The actions are: 
1. Transpose the grid
2. Compress the grid
3. Merge adjacent cells of the same value
4. Transpose the grid again
5. Check if the grid has been moved
6. Add a new random cell to the grid
7. Check if the game has ended or the player has won
8. Update the game board

Overall, this program provides a basic implementation of the "2048" game.

## Table of Contents

- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)
- [Dependencies](#Dependencies)

## Features

- Play 2048. 

## Installation

To install this project, follow these steps:
1. Clone the repository to your local machine:
```
git clone https://github.com/devvyyxyz/python-2048
```
2. Navigate to the project directory:
```
cd python-2048
```
3. Set up any required configuration files or environment variables as specified in the project documentation.
4. Run the project:
```
python main.py
```

# Dependencies

The program requires the Tkinter GUI library to be installed, which is usually included with Python.

## Usage

- Use arrow keys to move tiles up, down, left, or right.
- Press ESC to exit the game at any time.

## Contributing

Contributions are not being taken.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
