# N-Queens Problem
The N-Queens problem is a classic puzzle where the goal is to place N queens on an N×N chessboard in such a way that no two queens attack each other. In other words, no two queens can share the same row, column, or diagonal.

### Approaches Used
**1. Constraint Propagation and Backtracking**
This approach involves using constraint propagation techniques to efficiently explore the search space and backtrack when a conflict is encountered. The algorithm iteratively places queens on the board while maintaining constraints to ensure no conflicts occur. Backtracking is employed to undo incorrect placements and try alternative positions until a valid solution is found.

**2. Simulated Annealing**
Simulated Annealing is a probabilistic optimization algorithm inspired by the annealing process in metallurgy. It involves using a temperature parameter to control the probability of accepting unfavorable moves during the search. The algorithm explores the solution space by iteratively adjusting the positions of queens to reduce conflicts.

**3. Genetic Algorithms**
Genetic Algorithms are search heuristics inspired by the process of natural selection. The algorithm involves representing potential solutions (individuals) as chromosomes and applying genetic operations like crossover and mutation to evolve better solutions over generations. Fitness evaluation ensures that only valid and conflict-free solutions survive and reproduce.

A report word file discussing the results of the approaches is available in italian