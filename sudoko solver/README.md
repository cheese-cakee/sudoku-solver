Sudoku Solver in C
A command-line Sudoku Solver implemented in C using the backtracking algorithm. This project demonstrates the application of recursion and constraint satisfaction techniques to solve standard 9x9 Sudoku puzzles efficiently.

Features
Solves any valid 9x9 Sudoku puzzle using backtracking.

Input puzzles via standard input, file, or hardcoded array.

Simple and efficient algorithmic implementation.

Clean and modular C codebase.

Algorithm Overview
The solver uses a backtracking algorithm, which is a form of depth-first search. The idea is to fill empty cells one by one by trying all digits (1 to 9) and backtracking when a conflict arises (i.e., when the Sudoku rules are violated).

Steps:
Find an empty cell.

Try placing digits 1 through 9.

For each digit:

If it doesn't violate Sudoku constraints (row, column, box), place it.

Recurse to solve the rest of the board.

If it leads to a dead end, reset the cell (backtrack) and try the next digit.

Continue until the board is filled or no solution exists.

You may modify the source to:

Being able to solve 18X18 puzzles.

Input command from Users.

Add Colours for better Interactivity.