# Algorithms

**NOTE** This document will contain information about Computer Algorithms and Big O notation.

## Big O Notation

Big O - the runtime of an algorithm based on the input size.

You can use the Master Theorem to calculate Big O of a function. 

```If T(n) = aT(|n/b|) + O(n^d), where a>0,b>1,& d>=0 THEN

      |if d > log_b(a) 	THEN O(n^d)
T(n) =|if d = log_b(a) 	THEN O(n^d log n)
      |if d < log_b(a) 	THEN O(n^log_b(a))

n is the size of the input, 
a is the number of subproblems, 
b is size of partition in each recursive call 
```


The chart below shows the Big O notation from Fast to Slow:

| O(1) | O(log n) | O(sqrt(n)) | O(n) | O(n log n) | O(n^2) | O(n^3) | O(2^n) | O(n^n) | O(n!) |

## Divide and Conquer Algorithms
What is a divide and conquer algorithm?
-	Divide and conquer solves problems by breaking a problem into smaller subproblems, recursively solving the subproblems and appropriately combining their answers.

### Binary search
- The idea behind binary search is to split the search in half, thus the runtime would be O(log n)

### Merge Sort
- The idea behind merge sort is .... todo O(n log n)

## Dynamic Programming
What is dynamic programming?
-	DP is a way to solve optimization problems such as min, max, count, exact match
-	DP is an algorithmic paradigm where a large problem is solved by identifying a collection of similar smaller subproblems that are tackled one by one in a DAG - Directed Acyclic Graph.
-	In the DAG of DP the nodes are subproblems and the edges are their dependencies.
-	It is helpful to create a decision tree and then a tabulation to help yourself solve a DP problem.
-	The key feature of DP is reusing subproblems to solve the next subproblem
-	The subproblem is in terms of a prefix or suffix of the input, thus, a[1..i] instead of a[1..n] where n is the total number of items and i is the number of items at the current subproblem.
-	You want to create base cases after you identify your recurrence 
-	In DP you will be looking back at previously answer subproblems and the problem is always the same
-	Major Types of DP problems LIS, LCS, Knapsack 0/1, Knapsack Unlimited, CMM


## Graph Algorithms

### Explore

### Depth First Search - DFS

### SCC

### Topological Sort

### Breadth First Search - BFS

### Dijkstra single source shortest path algorithm

### Bellman-Ford single source shortest path algorithm

### Floyd-Warshall all pairs shortest path algorithm

### Prims MST algorithm

### Kruskal MST algorithm

## NP Completeness
