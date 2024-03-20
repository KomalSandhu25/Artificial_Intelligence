# Artificial_Intelligence

The code for the given repo is private.

The private repo contains implementation of different AI algorithms such as 
1. **SEARCH**:

   **Problem Statement**: calculate a route between two points in Romania while seeking to minimize time and space cost. 
   **Algorithms**:
   1. Implemented **Priority Queue** to order search frontier. 
   2. Implemented **Breadth first search** on the graph. It returns a path of nodes from a given start node to a given end node, as a list.
   3. Impelmented **uniform-cost search**, using PriorityQueue as the frontier. It return a path from the start to the goal node as a list of nodes.
   4. Implemented **A-star search** using Euclidean distance as heuristic.
   5. Implemented bidirectional **uniform-cost search**. This requires starting the search at both the start and goal nodes.
   6. Implemented bidirectional **A-star search**. Here we calculate a heuristic for both the start-to-goal search and the goal-to-start search. Optimal path calculated is the same path found via unidirectional UCS and A*.
   7. Implemented **tridirectional search** using UCS. Starting from each goal node, performed a uniform-cost search and keep on expanding until two of the three searches meet.

2. **GAME PLAY**:
   **Problem statement**: AI that can play and win a game of Castle Isolation.
   **Algorithm**:  
   1. Implemented **Minimax algorithm**. Defeated a Random Player >=90% of the time.
   2. Implemnted **Alpha Beta pruning**. Minimax level 2 >= 70% of the time.

3. **BAYES NETWORK**:
   **Problem Statement**: Build a Bayesian networks to efficiently calculate the answer to probability questions concerning discrete random variables.
   1. Setting the probabilities, performing inference, sampling and finally building the network. Perfomed Posterior distribution.
   2. Implemented Gibbs sampling and Metropolis-Hastings sampling to idenitfy which works better.
   
4. **DECISION TREE**:
   **Algorithms**:
   1. Implemnted **Decision tree** from scratch.
   2. Implemented **Random forest**.
  
6. **GAUSSIAN MIXTURE MODEL**:
   1. **k-Means Clustering** 
   2. **Gaussian Mixture Model** 
   3. **Bayesian Information Criterion**: Balance the goodness of fit of a model with the complexity of the model, penalizing models that are more complex 

