#CardGameAI - Lab: BFS and DFS for Card Matching Puzzle

This repository contains an implementation of Breadth-First Search (BFS) and Depth-First Search (DFS) algorithms to solve a card matching puzzle. The goal of the puzzle is to uncover matching pairs of cards on a randomly shuffled 7x8 grid. The game starts with all cards hidden (blank), and the algorithms work towards uncovering all pairs.

Features:

Randomized game board generation: The game board is initialized with shuffled card pairs.

BFS-based search: Uncovers matching pairs by exploring the grid layer by layer.

DFS-based search: Uncovers matching pairs by following a single path at a time.

Visual representation: Uses ANSI color codes to display red and black suits, making the board more readable.

Step-by-step search visualization: Prints the search process, showing how each algorithm explores the board.

File Overview:

Lab8_BFS_DFS.ipynb: Jupyter Notebook containing the implementation of both algorithms.

initial_boards(): Generates the randomized game board and a blank board.

bfs_match_all_pairs(): Implements BFS to find and reveal card pairs.

dfs_match_all_pairs(): Implements DFS to find and reveal card pairs.

auto_solve_game_BFS(): Runs BFS-based game-solving.

auto_solve_game_DFS(): Runs DFS-based game-solving.

How to Run:

Open the Jupyter Notebook (.ipynb).

Run the auto_solve_game_BFS() or auto_solve_game_DFS() function to visualize how each algorithm solves the puzzle.

This project demonstrates the differences in search strategies between BFS and DFS in a practical game scenario.
