# M.I.N.E.: Minesweeper Intelligent Navigation and Evaluation

## Introduction
This Python script offers a unique twist on the classic Minesweeper game by introducing real-time probabilistic analysis. Built with the `tkinter` library for the graphical interface, the game helps players by displaying the likelihood of mines being present in adjacent cells.

## Game Overview
M.I.N.E. enhances traditional Minesweeper by providing strategic probability analysis for neighboring cells. When a cell is opened, M.I.N.E. calculates and displays the probability of adjacent cells containing mines, helping players make more informed decisions based on these probabilities.

## How to Use
### Starting the Game
1. Ensure Python is installed on your computer.
2. Run the script using Python. You can start the game by following these steps:
    - Open a terminal or command prompt, navigate to the folder containing the script, and run:
      ```bash
      python filename.py
      ```
      Replace `filename.py` with your script's name.
    - Open the script in IDLE (Integrated Development and Learning Environment) and run it by selecting `Run > Run Module` from the menu.
    - If using an IDE like PyCharm or Visual Studio Code, open the script and run it by clicking the "Run" button or using the appropriate shortcut.
   
After running the script, the game window will appear.

### How to Play
- Left-click on a cell to reveal what's underneath.
- The game ends if you click on a mine, revealing all mines, or if you successfully reveal all non-mine cells.

## Game Features
- **Adjacent Probabilities:**
    - When a cell is revealed, the game calculates and displays the probability of adjacent cells containing mines.
    - Probabilities are shown as percentages on the buttons.
- **Auto-Clearing of Empty Areas:**
    - Revealing an empty cell will automatically clear all adjacent empty cells, displaying their contents.

## Class Structure
- **Cell Class:**
    - Represents an individual cell on the game board.
    - Tracks whether the cell is open, holds the probability array, monitors neighboring blocks, and more.
- **Minesweeper Class:**
    - Manages the overall game mechanics.
    - Responsible for setting up the game board, placing mines, revealing cells, updating probabilities, and handling player interactions.

## Key Functions
- **create_game_board:**
    - Sets up the GUI by creating buttons for each cell on the game board.
- **initialize_game:**
    - Prepares the game by placing mines and establishing relationships between neighboring cells.
- **reveal_cell:**
    - Reveals the content of a cell when the player clicks on it.
    - Manages mine explosions and the auto-clearing of empty areas.
- **update_probabilities:**
    - Calculates and updates the probabilities of mines in adjacent cells as the game progresses.

## Additional Information
- The game ends automatically when all mines are revealed or when all non-mine cells are opened.
- The script is designed to handle left-clicks for revealing cells.
- Probabilities are updated in real-time as the game unfolds.

## Dependencies
- Python 3.x
- Tkinter (typically included with Python installations)

## Development Environment
This script was developed and tested in a Python environment.

## Disclaimer
This game is intended for entertainment purposes and does not guarantee the accuracy of probabilities or the absence of bugs.

## Authors
-Karan Ganeshwala B22ES019

-Yash Golani B22ME072  
