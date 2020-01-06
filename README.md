# Sudoku-using-recursion-js

Sudoku puzzles are very famous in Japan. 
Sudoku puzzles are solved by logic and no math is required. 
It consists of a grid which is usually made up of nine rows, nine columns, and nine boxes that are separated by thicker, darker lines. Some of these boxes will contain numerals from 1 to 9. 
To solve the puzzle, a person must fill in all the empty squares without using the same numeral twice in each column, row, or box, and without changing the numerals that are already in the grid.

Used a backtracking algorithm to solve the puzzle.

The algorithm assumes a possible number in an empty spot and tries to solve the puzzle.

If the code becomes unsolvable (i.t the assumption is wrong) then the asumption is rejected and a different possible number is assumed. 

This goes on until the all the numbers in the empty spots are assumed correctly i.e the puzzle is solved.
