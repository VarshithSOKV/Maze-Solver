# Maze-Solver

Project Overview:
The project aims to solve maze-related problems using the principles of Markov Decision Processes (MDP). It includes two components - a maze solver and a maze encoder. Both components utilize MDP to navigate through mazes, compute optimal paths, and encode maze information.

Project Components:

1) Maze Solver (Maze_planner.py):

 - This script reads input from a file and represents a maze as an MDP.
 - It utilizes the Ford-Fulkerson algorithm for maximum bipartite matching to create a graph representation of the maze.
 - The script then calculates the optimal path from the start to the end point using Value Iteration, taking into account rewards and transitions.
 - The optimal path is printed as a sequence of directions (N, S, E, W) to navigate through the maze.


2) Maze Encoder (Maze-encoder.py):

 - This script also reads input from a file and models a maze as an MDP.
 - It calculates the optimal value function V for each state in the maze using the Bellman equation and Value Iteration.
 - The resulting V values are printed as the output, representing the value of each state in the maze.


3) Project Goals and Achievements:

 - The project successfully demonstrates the application of MDP in solving maze-related problems.
 - It provides solutions for finding optimal paths in mazes and encoding maze information.
 - Both components are capable of handling various types of mazes with different configurations.
 - The code is modular and can be easily adapted for different maze-solving tasks.
