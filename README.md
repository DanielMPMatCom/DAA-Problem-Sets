# Problem Set Solutions for NP-Completeness, DP, Greedy, Flow, and Divide and Conquer


<img src="np.jpeg" alt="np" width="400" height="400">


This repository contains solutions to a series of problem sets covering topics in:
- **NP-Completeness**
- **Dynamic Programming (DP)**
- **Greedy Algorithms**
- **Flow Algorithms**
- **Divide and Conquer**

## Solved Problems

### NP-Completeness
- **Exact Cover**
- **3-Coloring**
- **Chromatic Number**
- **Maximum Clique**
- **Clique Cover**
- **Dominant Set**
- **Feedback Node Set** 
- **Feedback Arc Set**
- **NAE 4-SAT**
- **NAE 3-SAT**
- **Max Cut**
- **Domatic Number**

### Dynamic Programming, Greedy, Divide and Conquer, Flow


#### Dynamic Programming
Dynamic Programming (DP) is particularly useful when a problem exhibits overlapping subproblems and an optimal substructure. By breaking down a problem into simpler subproblems, DP solves each smaller case once and stores the result, which can later be reused. This approach can be adapted, for example, to count the number of ways to color a graph or to compute the optimal configuration in partitioning or selection problems, although it may be combined with other strategies to manage high complexity.

#### Greedy Algorithms
Greedy algorithms build a solution piece by piece by always choosing the next piece that offers the most immediate benefit. While greedy methods do not guarantee an optimal solution for all problems—particularly for NP-hard problems like the Maximum Clique or Max Cut—they often provide a fast and reasonably good heuristic, making them attractive for large input sizes where exact computation is impractical.

#### Divide and Conquer
Divide and Conquer decomposes a problem into independent subproblems, solves each recursively, and then combines their results. This strategy is effective in problems where the structure of the input naturally allows segmentation, as in certain graph partitioning tasks or when filtering through potential combinations in set-based problems. Although it might not yield exact solutions for every NP-hard problem, it can substantially reduce computational complexity through parallelization and problem size reduction.

#### Flow-Based Methods
Flow-based methods leverage network flow algorithms, such as the Ford-Fulkerson method or its variants, to model and solve problems that can be reduced to a flow network. For instance, certain formulations of the Max Cut problem can be transformed into a flow problem, allowing the use of well-established techniques for solving network flow efficiently. Similarly, flow techniques can help in problems that require balancing competing constraints, such as those involving feedback sets.

Overall, these strategies—often used in combination—provide a diverse toolkit to design approximation algorithms, heuristics, or exact methods for tackling complex graph and constraint satisfaction problems. The choice of strategy depends on the problem structure, computational resources, and the desired trade-off between speed and accuracy.