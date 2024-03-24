# Sudoku Solver

## Overview
This Sudoku solver is a Java-based program that uses the backtracking algorithm to efficiently solve Sudoku puzzles.

## Sudoku Rules
Sudoku is a logic-based number placement puzzle. The objective is to fill a 9x9 grid with digits so that each column, each row, and each of the nine 3x3 subgrids contains all of the digits from 1 to 9. Here are the rules:
1. Each row must contain the digits 1-9 without repetition.
2. Each column must contain the digits 1-9 without repetition.
3. Each of the nine 3x3 subgrids must contain the digits 1-9 without repetition.

## Backtracking Algorithm
The backtracking algorithm is a recursive algorithm used to solve constraint satisfaction problems, such as Sudoku puzzles. Here's how it works:
- Start with an empty cell on the Sudoku board.
- Try all possible numbers (1-9) for the empty cell.
- If a number is valid (i.e., it doesn't violate Sudoku rules), move to the next empty cell and repeat the process recursively.
- If there are no valid numbers for the current cell, backtrack to the previous cell and try a different number.
- Repeat this process until the entire Sudoku puzzle is filled, satisfying all constraints.

## How to run 🤔
To use the Sudoku solver, simply run the Java program and input the initial Sudoku board. The solver will then proceed to solve the puzzle and display the solution.
