# CDoku-Solver

This is a sudoku solver that can solve up to 3 star puzzles, probably.
written in C++ for my programming class. 

## Get started

Clone the repo and enter it

#### Compile it and run
```
$ make && ./CDoku test_puzzles/sudoku.txt -p
```
#### Usage
```
Command options:
  -o <file>    write solved puzzle to <file>
  -p           print to console
  -r <row>     solve just row <row>, only takes numbers 1-9
  -c <col>     solve just column <col>, only takes numbers 1-9
  -U           pretty UI, all other args are ignored and the hand-holding ui will walk you through this

Example Usage:
  ./CDoku sudoku.txt -o solved.txt        Solves a puzzle in file sudoku.txt and writes out to solved.txt
```

### History

Myself (Robindiddams) and two friends built this for a programming class.
I wanted to continue development (and keep practicing c/c++) and I love the git community so here it is. PR's welcome!