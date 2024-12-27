# 🧩 N-Puzzle Problem Solution
This project presents the solution to the N-Puzzle (Sliding Puzzle) problem using C++. The implementation includes advanced algorithms and data structures to ensure efficiency and accuracy.

# 🔧 Technical Details
# Priority Queue
A priority queue is utilized to sort the possible states of the N-Puzzle by their lowest cost.

# Heuristic Functions
Two heuristic methods are applied to estimate the proximity of the current state to the solution:

The number of misplaced tiles.
The Manhattan distance of each tile to its target position.
# A Search Algorithm*
The algorithm combines the actual cost of reaching a state and the heuristic estimation to find the optimal solution.

# Data Structures

vector<int>: Used to represent the puzzle states.
set: Stores visited states to prevent redundant processing.
vector<string>: Records the moves required to solve the puzzle.
Dynamic Puzzle Size
The implementation supports any size of N-Puzzle (e.g., 3x3, 4x4) by dynamically adjusting based on input parameters.

# Valid Moves
The algorithm ensures only valid moves (UP, DOWN, LEFT, RIGHT) are applied based on the position of the empty tile.
