# Mechanical-Puzzles



Here is some work on mechanical puzzles that I've done. Currently, we have three files in this repo

Rubik's cube, a working Rubik's cube object that rotates as a real cube does. Solution algorithm to come.

Grecian computer (github version), an interesting puzzle based on spinning wooden wheels to make a common sum. Pictures were originally included in the original Jupyter notebook, but github had issues with that so I seperated two images out (a picture of the puzzle and a picture of the solution) and deleted some others that I used in the original notebook.  

The slider puzzle notebook is a slider (or 15) puzzle solver. It works on stages, solving the puzzle as a human would -- by first placing the 1, then the 2, the completing the top row, then completing the left column. I did it this way in order for it to run as fast as possible, it does not guarentee an optimal length solution.  The code can be easily changed to use A* (how it accomplishes each of its subgoals) in order to achieve an optimal solution at the cost of a higher runtime.
