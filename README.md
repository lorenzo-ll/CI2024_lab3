# CI2024_lab3
This code implements an A* algorithm. We used a combination of Manhattan Distance, the sum of the vertical and horizontal distances of each tile from its goal position, and Linear Conflict, additional penalties for tiles that are in the same row or column but in the wrong order. We're also checking if the puzzle in itself is solvable, given the randomness of this problem. 

A state is solvable if and only if:

For odd-width boards: The number of inversions plus the row number of the blank space (counting from bottom, starting at 1) must be even
For even-width boards: The number of inversions plus the row number of the blank space (counting from bottom) must have the same parity as the blank's row number counting from bottom

Please note that execution times might vary a lot depending on the starting state.

I worked with Giorgio Rondinone (s332156) and Simone Scalora (s329444)
