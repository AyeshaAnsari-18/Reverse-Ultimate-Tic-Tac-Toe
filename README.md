# 🧠 Ultimate Tic-Tac-Toe with AI (Python + Tkinter)

This is a Python implementation of **Ultimate Tic-Tac-Toe**, a strategic extension of classic Tic-Tac-Toe featuring a 3x3 grid of mini-boards. The game includes a GUI built with **Tkinter** and an **AI opponent powered by the Minimax algorithm**.

## 🎮 Gameplay Rules

- The main board consists of 9 smaller Tic-Tac-Toe boards.
- Players take turns placing their symbol (X or O).
- Your move determines the board where your opponent must play next.
  - Example: If you place your mark in the top-left cell of a mini-board, your opponent must play in the top-left mini-board next.
- If the required mini-board is full or already won, your opponent can play in **any** board.
- Win a mini-board by getting 3 of your marks in a row inside it.
- Win the game by winning 3 mini-boards in a row on the main grid.

## 🤖 Features

- **AI Opponent**: Implements the Minimax algorithm with limited depth for performance.
- **Reversed Rule Handling**: If a target mini-board is full or won, the player is allowed to move anywhere.
- **Visual Indicators**: Highlights current board to play, shows mini-board winners, and displays overall winner.
- **Object-Oriented Design**: Clean structure using classes for `MiniBoard`, `UltimateTicTacToe`, and the GUI.

## 🛠 Technologies Used

- **Python 3**
- **Tkinter** (for GUI)
- **Minimax** Algorithm (for AI logic)
- **OOP** Principles

## 🚀 Getting Started

1. Make sure Python 3 is installed.
2. Clone the repository or download the files.
3. Run the main script:

```bash
python Reverse_Ultimate_TicTacToe.ipynb
