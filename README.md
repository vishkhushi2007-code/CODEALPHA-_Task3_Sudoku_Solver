# Task 3: Sudoku Solver (C++)

This folder contains **two versions** of the Sudoku Solver:

## 1. Console Version (No extra libraries needed)
**File:** `sudoku_console.cpp`

### Compile & Run:
```bash
g++ sudoku_console.cpp -o sudoku
./sudoku
```

## 2. GUI Version (Qt)
**Files:** `SudokuSolver.pro`, `main.cpp`, `mainwindow.h`, `mainwindow.cpp`

### Requirements:
- Qt 5 or Qt 6
- Qt Creator (recommended)

### How to Run:
1. Open `SudokuSolver.pro` in Qt Creator
2. Configure kit → Click Run

### Features (GUI):
- Interactive 9×9 grid
- Visual 3×3 box borders
- Solve / Clear / Load Example buttons
- Full backtracking algorithm

## Algorithm (Both versions)
- Represent board as 2D array
- Backtracking to fill empty cells
- Validate row, column, and 3×3 subgrid
- Recursively try numbers 1-9 until solved
