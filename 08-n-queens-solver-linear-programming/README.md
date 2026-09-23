# N-Queens Solver with Linear Programming

**Notebook:** [`n_queens_solver.ipynb`](n_queens_solver.ipynb)

## Problem
Place N queens on an N×N board so that no two attack each other.

## Data
None; N is a parameter.

## Approach
- Binary variable per square.
- Constraints for rows, columns, and both diagonal directions.
- Solved with the CBC solver through PuLP.

## Result
The solver finds an **optimal (valid) placement**, re-verified by re-running the notebook.

---
*Group project from the Vert 2024 data trainee program. See the [main README](../README.md) for context.*
