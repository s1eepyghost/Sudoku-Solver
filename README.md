# Sudoku Solver (JavaScript)

## Overview

This Sudoku Solver is a JavaScript program designed to solve Sudoku puzzles of varying difficulty levels. Sudoku is a popular number-placement puzzle that requires logical thinking and pattern recognition to fill a 9x9 grid with digits from 1 to 9.

## Features

- **Solver Algorithm**: The program uses a backtracking algorithm implemented in JavaScript to systematically fill in the Sudoku grid, ensuring that each digit is placed according to the rules of the game.

- **Interactive Web Interface**: Users can interact with the solver through a web interface, where they can input Sudoku puzzles and see the solutions dynamically.

- **Clear Output**: Once solved, the program provides a clear and formatted output of the completed Sudoku grid on the web page.

## Getting Started

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/yourusername/sudoku-solver-js.git
   cd sudoku-solver-js
   ```

2. **Open `index.html`:**
   Open the `index.html` file in your preferred web browser.

3. **Input Sudoku Puzzle:**
   Enter the Sudoku puzzle in the provided input fields. Use zeros or leave empty for empty cells.

4. **Click "Solve":**
   Click the "Solve" button, and the solved Sudoku grid will be displayed on the web page.

## Example

```javascript
// Example Sudoku Puzzle
const inputGrid = [
    [5, 3, 0, 0, 7, 0, 0, 0, 0],
    [6, 0, 0, 1, 9, 5, 0, 0, 0],
    [0, 9, 8, 0, 0, 0, 0, 6, 0],
    [8, 0, 0, 0, 6, 0, 0, 0, 3],
    [4, 0, 0, 8, 0, 3, 0, 0, 1],
    [7, 0, 0, 0, 2, 0, 0, 0, 6],
    [0, 6, 0, 0, 0, 0, 2, 8, 0],
    [0, 0, 0, 4, 1, 9, 0, 0, 5],
    [0, 0, 0, 0, 8, 0, 0, 7, 9]
];

// Output
/*
5 3 4 | 6 7 8 | 9 1 2
6 7 2 | 1 9 5 | 3 4 8
1 9 8 | 3 4 2 | 5 6 7
------+-------+------
8 5 9 | 7 6 1 | 4 2 3
4 2 6 | 8 5 3 | 7 9 1
7 1 3 | 9 2 4 | 8 5 6
------+-------+------
9 6 1 | 5 3 7 | 2 8 4
2 8 7 | 4 1 9 | 6 3 5
3 4 5 | 2 8 6 | 1 7 9
*/

```

## Contributing

If you'd like to contribute to the development of this Sudoku Solver, please follow the guidelines in the `CONTRIBUTING.md` file.

## License

This Sudoku Solver is open-source and available under the [MIT License](LICENSE).

---

Feel free to reach out if you have any questions or suggestions!