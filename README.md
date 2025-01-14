# Gomoku_board_game

## Description
This project is a Python implementation of the classic board game **Gomoku** (also known as Five in a Row), a popular strategy game originating from East Asia. Two players take turns placing stones on a square grid, with the goal of being the first to align five stones in a row horizontally, vertically, or diagonally. The program simulates the gameplay, enforces the rules, and determines the winner or a draw based on the state of the board.

---

## Game Rules
1. The game is played on a rectangular grid (default size: 9x9).
2. Players alternate turns to place their stones (black or white) on vacant intersections of the grid.
3. The player using black stones always starts the game.
4. The game ends when:
   - One player creates an unbroken line of five stones (horizontally, vertically, or diagonally).
   - The board is completely filled without any player achieving a winning line, resulting in a draw.

---

## Features
- **Dynamic Board Sizes:** The program allows customizable board dimensions.
- **Turn-based Gameplay:** Players alternate turns to ensure fair play.
- **Win Detection:** Automatically checks for a winning line after each move.
- **Draw Detection:** Identifies when the game ends in a draw if the board is filled.
- **Error Handling:** Prevents invalid moves such as placing stones on already occupied spots.

---

## Getting Started

### Prerequisites
- Python 3.6 or higher
- 
