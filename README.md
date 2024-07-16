# SudokuHex Solver

A Java-based solver for 16x16 hexagonal Sudoku puzzles.

## Overview

This project provides a solution for 16x16 hexagonal Sudoku puzzles. It uses a backtracking algorithm to explore possible solutions and solve the puzzle. Each cell in the Sudoku grid can contain a value from 0-9 or a-f, following hexadecimal notation.

## Features

- Solves 16x16 hexagonal Sudoku puzzles.
- Uses a backtracking algorithm to fill in the puzzle.
- Supports both uppercase and lowercase input for puzzle representation.

## Requirements

- Java Development Kit (JDK) 8 or higher

## How to Run

1. Clone this repository or download the source code.
2. Open the project in your preferred Java IDE or text editor.
3. Compile and run `SudokuHex.java`.

### Example

To solve a Sudoku puzzle, you can instantiate a `SudokuHex` object with the puzzle template and call the `solve` method:

```java
public class Main {
    public static void main(String[] args) {
        String template = "your_sudoku_template_here";
        SudokuHex sudoku = new SudokuHex(template);
        sudoku.solve();
        System.out.println(sudoku);
    }
}
