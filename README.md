# Algorithm and Data Structure

Implement classical algorithm and data structure from scratch (including operating system related algorithm)

## Problem

Book

* Introduction to Algorithm 3ed. - alias Cormen
* Data Structure and Algorithm in C++ - alias DSA

---

| Class                        | Subject                                                                                                | Strategy     | Data Structure | Textbook                  | Remark                                                      |
| ---------------------------- | ------------------------------------------------------------------------------------------------------ | ------------ | -------------- | ------------------------- | ----------------------------------------------------------- |
| Knapsack                     | 0-1 Knapsack                                                                                           | DP           |                | Cormen-Ch16.2             |
| Knapsack                     | Fractional Knapsack                                                                                    | Greedy       |                | Cormen-Ch16.2             |
| Minimum Spanning Tree        | Kruskal's algo.                                                                                        |              | Graph→Tree     | Cormen-Ch23.2             |
| Minimum Spanning Tree        | Prim's algo.                                                                                           |              | Graph→Tree     | Cormen-Ch23.2             |
| Single-Source Shortest Paths | Bellman-Ford algo.                                                                                     |              | Graph          | Cormen-Ch24.1             |
| Single-Source Shortest Paths | Dijkstra's algo.                                                                                       |              | Graph          | Cormen-Ch24.3             |
| All-Pairs Shortest Paths     | Floyd-Warshall algo.                                                                                   |              | Graph          | Cormen-Ch25.2             |
| Classic                      | [Matrix-Chain Multiplication](Problem/Classic/MatrixChainMultiplication.ipynb)                         | DP           |                | Cormen-Ch15.2             |
| Classic                      | 數字三角形, [Maximum Path Sum in a Triangle](https://www.geeksforgeeks.org/maximum-path-sum-triangle/) | DP           |                |
| Classic                      | Traveling Salesperson (Salesman) (TSP)                                                                 | Backtracking | Tree(Graph)    | Cormen-Ch35.2             | NP-hard, O(n!)                                              |
| Classic                      | Eight Queens Puzzle (Problem)                                                                          | Backtracking | Tree(Graph)    |                           | NP-complete                                                 |
| Classic                      | Maximum Clique Problem                                                                                 | Backtracking |                |                           | [wiki (temp)](https://en.wikipedia.org/wiki/Clique_problem) |
| Classic                      | Graph Coloring (vertex coloring, k-coloring)                                                           | Backtracking |                | Cormen-Ch34.4-Problem34.3 | NP-complete                                                 |
| Network FLow                 | Ford-Fulkerson                                                                                         |
| Network FLow                 | Floyd                                                                                                  |

### Problem Class Categories

(A problem class may be covered in several categories)

* Combinatorial Optimization (組合優化) - use Backtracking, Branch and Bound
    * Traveling Salesman Problem
    * Minimum Spanning Tree
    * Knapsack

## Data Structure

List, Array

* Linked List
* Double Linked List
* Queue
* Stack

Tree

* Tree infrastructure
* Binary Search Tree
* N-ary Tree
* Trie (Prefix Tree)
* Min / Max Heap

Graph

* Graph infrastructure

Hash

* Hash infrastructure

## Algorithm

Searching

Sorting

Branch and Bound (alias B&B) (分支限界)

Linear Programming (alias LP) (線性規劃)

[Network Flow (網路流)](Notes/Algorithm/NetworkFlow/NetworkFlow.md)

### Strategy

Greedy

Divide and Conquer (alias DC)

Dynamic Programming (alias DP) (動態規劃)

Backtracking - Tree Search

### Graph-based

Depth First Search

Breadth First Search

### Tree-based

DFS-based

* Pre-order Traversal
* In-order Traversal
* Post-order Traversal

BFS-based

* Level-order Traversal

## [Operating System](https://github.com/daviddwlee84/OperatingSystem)

Cache

* First in first out (FIFO)
* Last in first out (LIFO)
* Least recently used (LRU)
* Time aware least recently used (TLRU)
* Most recently used (MRU)
* Pseudo-LRU (PLRU)
* Random replacement (RR)
* Segmented LRU (SLRU)
* Least-frequently used (LFU)
* Least frequent recently used (LFRU)
* LFU with dynamic aging (LFUDA)
* Low inter-reference recency set (LIRS)
* Adaptive replacement cache (ARC)
* Clock with adaptive replacement (CAR)
* Multi queue (MQ)

Scheduling

* Process Scheduler
    * Long-term scheduling
    * Medium-term scheduling
    * Short-term scheduling
* Scheduling Discipline (algo.)
    * First come, first served
    * Priority scheduling
    * Shortest remaining time first (SJF)
    * Fixed priority pre-emptive scheduling
    * Round-robin scheduling
    * Multilevel queue scheduling
    * Work-conserving schedulers
    * Scheduling optimization problems
    * Manual scheduling

Deadlock Prevention

* Banker's algorithm
* Preventing recursive locks

Concurrency (just notes)

* Critical Section
* Mutex Semaphore (aka Mutex)
* Counting Semaphore (aka Semaphore)
* Spin-lock (aka Spinlock)

Deadlock & Starvation (just notes)

## Links

* [什麼是動態規劃？意義？](https://www.zhihu.com/question/23995189/answer/35429905)
* [TheAlgorithms/Python](https://github.com/TheAlgorithms/Python) - All Algorithms implemented in Python
* [**huaxz1986/cplusplus-_Implementation_Of_Introduction_to_Algorithms**](https://github.com/huaxz1986/cplusplus-_Implementation_Of_Introduction_to_Algorithms) - C++ Implementation of the book - Introduction to Algorithms
