# Artificial_Intelligence

The code for the given repo is private.

The private repo contains implementation of different AI algorithms such as 
1. **SEARCH**:

   **Problem Statement**: calculate a route between two points in Romania while seeking to minimize time and space cost. 
   **Steps Taken**:
   1. Implemented Priority Queue to order search frontier. 
   2. Implemented Breadth first search on the graph. It returns a path of nodes from a given start node to a given end node, as a list.
   3. Impelmented uniform-cost search, using PriorityQueue as the frontier. It return a path from the start to the goal node as a list of nodes.
   4. Implemented A* search using Euclidean distance as heuristic.
   5. Implemented bidirectional uniform-cost search. This requires starting the search at both the start and goal nodes.
   6. Implemented bidirectional A* search. Here we calculate a heuristic for both the start-to-goal search and the goal-to-start search. Optimal path calculated is the same path found via unidirectional UCS and A*.
   7. Implemented tridirectional search using UCS. Starting from each goal node, performed a uniform-cost search and keep on expanding until two of the three searches meet.

3. K-means algorithm
4. Minimax algorithm
5. Bayes Network
6. Decision trees

