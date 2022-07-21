# Sudoku Solver
Sudoku is a puzzle in which players insert the numbers one to nine into a grid consisting of nine squares subdivided into a further nine smaller squares in such a way that every number appears once in each horizontal line, vertical line, and square. This lightweight Sudoku Solver, gets the input of the available values and gives the solution through a 3-step procedure of validation, generative recursion and backtracking search.

## Working
### Rules of Sudoku
1. Each row must contain the numbers from 1 to 9, without repetitions.
2. Each column must contain the numbers from 1 to 9, without repetitions.
3. The digits can only occur once per block (nonet).

### Generative Recursion
Rearranges a problem into a series of smaller subproblems, which are then combined to find a solution. These sub-problems are often (but not always) the same kind of problem as the original. In our case, the parent problem is the blank spaces which are initially provided by the user. This is broken down into several subproblems ie. by adding new possible values and pruning the possibilities that break the rule.

### Backtracking Search
Backtracking is a general algorithm for finding solutions to some computational problems, notably constraint satisfaction problems, that incrementally builds candidates to the solutions, and abandons a candidate as soon as it determines that the candidate cannot possibly be completed to a valid solution. Upon the rule breakage, we backtrack and search for the next possible outcome in the recursion tree.

## Some Resources
```
Google font: https://fonts.google.com/specimen/Patrick+Hand

Toastify JS: https://apvarun.github.io/toastify-js/
```

## References
```
https://www.sudokuonline.io/tips/sudoku-rules

https://www.simplilearn.com/tutorials/data-structure-tutorial/backtracking-algorithm

https://github.com/JackHeTech/Sudoku-Solver
```

## Preview
![mockup](https://user-images.githubusercontent.com/76687631/180238032-717a4494-c5cb-47bc-9a8d-1f549e5af109.png)
