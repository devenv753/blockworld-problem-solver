Question: How does this Block World Solver code move blocks from the start state to the goal state?
This Block World Solver compares each block’s current position with its goal position. If a block is not in the right place, it moves the block step-by-step to the desired position. It repeats this until all blocks match the goal state.

Step-by-step Explanation of  solve_blocks Function: 
1.	Print Initial State:
The function first shows where each block is placed at the start. For example, block A is on B, block B is on the Table, etc.
2.	Print Goal State:
It then shows the desired final arrangement of the blocks, where each block should be at the end.
3.	Copy Current State:
It makes a copy of the starting positions so it can keep track of changes without modifying the original data.
4.	Compare Each Block’s Position:
For every block in the goal state:
o	It checks if the block is already where it should be.
o	If not, it prints a step showing the block being moved from its current position to the desired position.
5.	Update the Current State:
After moving a block, it updates the current positions to reflect the move.
6.	Repeat Until All Blocks Are in Place:
It continues checking and moving blocks one by one until all blocks match the goal state.
7.	Print Final State:
Finally, it prints the last arrangement of blocks confirming the goal is reached.


RUN: 
https://www.programiz.com/online-compiler/2sFoTpJDjI8yt
https://www.programiz.com/online-compiler/6FWVjgAnz9iVT
