# Solve Sudoku with AI

### Question 1 (Naked Twins)
Q: How do we use constraint propagation to solve the naked twins problem?  
A: By using constraint propagation we are applaying a restriction as many times as possible to simplify and eventually solve a problem.
    In Sudoku it's all about reducing the number of possible digits in each square so we can get to a solved puzzle with 1 digit per square and each digit appears once in each unit.
    The naked twins strategy is to identify boxes with the same 2 digits as only possibilities belonging to the same set of peers and eliminate those 2 numbers from those peers.
    I implemented it by using bits and pieces of both the eliminate and only choice function presented in class



### Question 2 (Diagonal Sudoku)
Q: How do we use constraint propagation to solve the diagonal sudoku problem?  
A: The Diagonal sudoku is a much simpler problem.
    A unit is defined as a set of 9 boxes, and in the implemented solution we already account for the fact that each unit can only have each digit once.
    well, the diagonal is just another set of 9 boxes so we just need to add it as a unit when the sudoku is diagonal.



### Code

* `solutions.py` - You'll fill this in as part of your solution.
* `solution_test.py` - Do not modify this. You can test your solution by running `python solution_test.py`.
* `PySudoku.py` - Do not modify this. This is code for visualizing your solution.
* `visualize.py` - Do not modify this. This is code for visualizing your solution.




