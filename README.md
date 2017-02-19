# Artificial Intelligence Nanodegree
## Introductory Project: Diagonal Sudoku Solver

# Question 1 (Naked Twins)
Q: How do we use constraint propagation to solve the naked twins problem?  
A: Our main goal is to reduce the search space for each iteration. In the naked twins approach, we have to find two boxes with the same two potential digits and the two boxes can either be in same rows or same columns or square. When we get the required two boxes that meet the conditions, it helps in constraining the other boxes in the unit and hence reducing our search space.

# Question 2 (Diagonal Sudoku)
Q: How do we use constraint propagation to solve the diagonal sudoku problem?  
A: For a diagonal Sudoku problem, the two diagonals are introduced as new units. Like we restricted the column, rows and squares from having the repeating values, we need to apply the same restriction on both the diagonals also. So to limit the search space for each iteration we have to use strategies like elimination, naked twins and only choice on diagonals.

### Install

This project requires **Python 3**.

We recommend students install [Anaconda](https://www.continuum.io/downloads), a pre-packaged Python distribution that contains all of the necessary libraries and software for this project. 
Please try using the environment we provided in the Anaconda lesson of the Nanodegree.

##### Solution Walkthrough with Pygame

![alt tag](https://github.com/anmolkhanna93/AIND-Sudoku/blob/master/solverDemo.gif)

### Code

* `solutions.py` - You'll fill this in as part of your solution.
* `solution_test.py` - Do not modify this. You can test your solution by running `python solution_test.py`.
* `PySudoku.py` - Do not modify this. This is code for visualizing your solution.
* `visualize.py` - Do not modify this. This is code for visualizing your solution.

### Visualizing

To visualize your solution, please only assign values to the values_dict using the ```assign_values``` function provided in solution.py

### Data

The data consists of a text file of diagonal sudokus for you to solve.
