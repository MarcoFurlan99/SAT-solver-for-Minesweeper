# SAT-solver-for-Minesweeper
A code that implements a SAT solver to Minesweeper. If no solution is found, uses model counting.

A game of Minesweeper is initialized. The algorithm starts with random guesses.
Once information is found, we encode it in SAT language. The algorithm finds mines and safe cell using a SAT solver.
If no safe cells nor mines are found, model counting is used to find the best guess (cell less likely to have a bomb).
Then repeats the process.

Most games will either end during the random guesses or get solved.

Scroll to the end of the code to see the algorithm at work!
