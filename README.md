# TIC-TAC-TOE-GAME
# Tic Tac Toe Game

Welcome to the **Tic Tac Toe** game, a simple console-based game written in C. This game allows you to play Tic Tac Toe against the computer. Enjoy the fun and try to beat the computer!

---

## Features
- Interactive gameplay.
- Clear and minimalistic UI in the console.
- Play as `X` while the computer plays as `O`.
- Randomized moves for the computer.
- Automatic win, lose, or tie detection.

---

## How to Play

1. Clone or download the repository to your local machine.
2. Compile the program using a C compiler (e.g., GCC).
   ```bash
   gcc -o tictactoe tictactoe.c
   ```
3. Run the executable:
   ```bash
   ./tictactoe
   ```
4. Follow the on-screen instructions:
   - You will be prompted to enter the row and column numbers (1-3) for your move.
   - The computer will make its move automatically.
   - The game continues until there is a winner or no free spaces left.

---

## Code Overview

### Functions

- **`resetBoard()`**
  Initializes the game board by resetting all spaces to `' '`.

- **`printBoard()`**
  Displays the current state of the board in a 3x3 grid format.

- **`checkFreeSpaces()`**
  Counts and returns the number of available spaces left on the board.

- **`playerMove()`**
  Handles the player's move by prompting for input and updating the board.

- **`computerMove()`**
  Generates a random move for the computer and updates the board.

- **`checkWinner()`**
  Checks the board to determine if there is a winner (Player, Computer, or Tie).

- **`printWinner(char winner)`**
  Displays the game result (win, lose, or tie).

---

## Example Gameplay

```
****************************************************
         Welcome to the Tic Tac Toe game!           
****************************************************

* Instructions

	Player 1 sign = X
	Player 2 sign = O

   |   |   
---|---|---
   |   |   
---|---|---
   |   |   

Enter row #(1-3): 1
Enter column #(1-3): 1

 X |   |   
---|---|---
   |   |   
---|---|---
   |   |   

   (Computer makes a move)

 X |   |   
---|---|---
   | O |   
---|---|---
   |   |   
```

---

## Winning Conditions
The game checks for a winner based on:
- Three consecutive marks (`X` or `O`) in any row.
- Three consecutive marks in any column.
- Three consecutive marks along either diagonal.

If all spaces are filled without a winner, the game results in a tie.

---

## Requirements
- A C compiler (e.g., GCC).
- Basic knowledge of terminal or command-line usage.

---

## Future Enhancements (Suggestions)
- Add a difficulty level for the computer.
- Implement a two-player mode.
- Enhance the UI for a more user-friendly experience.

---
