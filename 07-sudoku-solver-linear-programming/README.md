# Sudoku Solver with Linear Programming

**Notebook:** [`sudoku_solver.ipynb`](sudoku_solver.ipynb)

## Problem
Solve any valid Sudoku puzzle by modeling it as an optimization problem.

## Data
None; the puzzle is defined in the notebook.

## Approach
- Binary decision variables: one per (row, column, digit).
- Constraints: each cell holds one digit, and each row, column, and 3×3 box contains every digit once.
- Solved with the CBC solver through PuLP.

## Result
The solver returns an **optimal (valid) solution**, re-verified by re-running the notebook.

---
*Group project from the Vert 2024 data trainee program. See the [main README](../README.md) for context.*
