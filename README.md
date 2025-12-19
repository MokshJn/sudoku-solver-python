# Sudoku Solver (Backtracking)

A high-performance Python-based Sudoku solver that utilizes the **Backtracking algorithm** to solve 9x9 puzzles.

## Features
- **Efficient Search:** Uses recursive backtracking to find solutions.
- **Smart Pruning:** Implements constraint satisfaction logic to prune invalid search branches early, significantly reducing execution time.
- **Validation:** Includes robust input validation to ensure the initial board configuration is legal.
- **Performance:** Solves expert-level puzzles in sub-second time (typically < 0.01s).

## How it Works
The solver uses a **depth-first search** approach:
1. It picks an empty cell.
2. It attempts to place a digit (1-9) that doesn't violate Sudoku rules.
3. If a digit is placed, it moves to the next cell recursively.
4. If a dead end is reached (no valid digits), it **backtracks** to the previous cell and tries a different digit.

## Usage
1. Clone the repository:
   ```bash
   git clone [https://github.com/MokshJn/sudoku-solver-python.git](https://github.com/Mokshjn/sudoku-solver-python.git)
