# N_Queen
This is a N Queen Solver, I have used Hill Climbing Algorithm to implement it.

## Working:
#### Step 1) Start with a random Init State, with each column having only one Queen
#### Step 2) Calulate the Present Heuristic of the Arrengement, Here the Huristic funtion is simply the number of Attack Lines
#### Step 3) Move each queen to each valid position available one at a time and Finally move to the Minimun Heuristic position.
#### Step 4) Repeat Steps 2, 3 untill we get a 0 Heuristic Position. Also if the Heuristic Value doesn't change for a number of steps then Aboart as there might be no solution available for the given problem
