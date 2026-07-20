# LeetCode Warm Up on (Almost) Every Quant Prep Day

This is a repository tracking my LeetCode progress, targeting the following algorithms with complexity analyses. 

**Tier 1: Core Fundamentals & Highest ROI for Quant Risk**
| Rank | Algorithms | Total No. on LeetCode | Why It Matters for Quants|
|--- |--- |--- |--- |
| 1 | Array & Two Pointers | 2,451 | Basic data handling, memory locality, and two-pass array contractions |
| 2 | Dynamic Programming & Memoization | 709 | Essential for recursive optimisation, Markov chains, and option-pricing models. |
| 3 | Binary Search & Divide and Conquer | 410 | Crucial for continuous/discrete decision spaces and root-finding. |
| 4 | Hash Table & Hash Function | 868 | Fast $O(1)$ lookups, state mapping, and frequency aggregation. |
| 5 | Math, Number Theory & Combinatorics | 845 | Direct evaluation of modular arithmetic, prime factorisations, and permutations. |
| 6 | Sliding Window & Prefix Sum | 432 | Subarray tracking and $O(1)$ range-sum/aggregate queries. |
| 7 | Heap (Priority Queue) & Monotonic Queue | 244 | Real-time streaming metrics, top-$K$ tracking, and order-book logic. |
| 8 | Monotonic Stack & Stack | 252 | Next Greater Element patterns and linear-time array parsing. |

**Tier 2: Essential Advanced Patterns**
| Rank | Algorithms | Total No. on LeetCode | Why It Matters for Quants|
|--- |--- |--- |--- |
| 9 | Bit Manipulation & Bitmask | 343 | Low-level hardware efficiency, state packing, and fast binary arithmetic. |
| 10 | Matrix & Simulation | 488 | 2D spatial transformations, linear algebra grids, and procedural tracking. |
| 11 | Sorting, Merge Sort & Quickselect | 550 | $O(N log N)$ invariants, median finding and order statistics. |
| 12 | Depth-First Search (DFS) & Backtracking | 458 | Combinatorial state-space search and tree exploration. |
| 13 | Probability and Statistics & Brainteaser | 28 | Pure quant logic, expectation calculations, and stochastic riddles. |
| 14 | Breadth-First Search (BFS) & Shortest Path | 300 | Grid traversals, minimal transition sequences, and graph states. |
| 15 | Recursion | 51 | Master-theorem mechanics and call-stack trace analysis. |

**Tier 3: Specialised & Selective Coverage**
| Rank | Algorithms | Total No. on LeetCode | Why It Matters for Quants|
|--- |--- |--- |--- |
| 16 | Binary Tree & Binary Search Tree | 223 | Hierarchical data representation and balanced search tree mechanics. |
| 17 | Greedy | 470 | Local optimisation proofs (note: prioritise DP over pure Greedy heuristics). |
| 18 | Graph Theory & Union-Find | 286 | Connected components and relationship dependency modeling. |
| 19 | String, String Matching & Rolling Hash | 950 | Parsing and substring matching (stick strictly to fundamental string manipulation). |
| 20 | Design, Data Stream & Iterator | 169 | In-memory cache structures (LRU/LFU) and stream processing interfaces. |
| 21 | Topological Sort | 40 | Dependency resolution and Directed Acyclic Graph (DAG) ordering. |
| 22 | Game Theory | 30 | Minimax optimisation and game-state analysis (e.g., Nim game variants). |
| 23 | Counting & Counting Sort / Radix Sort | 221 | Non-comparison $O(N)$ sorting and bucketed distributions. |
| 24 | Linked List & Doubly-Linked List | 97 | Pointer manipulation and memory allocation fundamentals. |
| 25 | Geometry | 46 | Spatial calculations, convex hulls, and coordinate geometry. |

**Tier 4: Niche Topics**
| Rank | Algorithms | Total No. on LeetCode | Why It Matters for Quants|
|--- |--- |--- |--- |
| 26 | Advanced Tree Data Structures (Segment Tree, Binary Indexed Tree, Trie, Suffix Array) | 80+44+61+8 = 193 |--- |
| 27 | Advanced Graph Theory (Minimum Spanning Tree, Eulerian Circuit, Strongly Connected Component, Biconnected Component) | 6+3+2+1 = 12 |--- |
| 28 | Randomisation & Sampling (Randomised, Reservoir Sampling, Rejection Sampling) | 12+4+2 = 18 |--- |
| 29 | Advanced / Niche Maths & Algorithms (Ordered Set, Sweep Line, Interactive, Enumeration, Bucket Sort, Shell) | 79+8+25+153+6+4 = 196 |--- |

**Tier 5: Bonus Topics**
| Rank | Algorithms | Total No. on LeetCode | Why It Matters for Quants|
|--- |--- |--- |--- |
| 30 | Database | 310 |--- |
| 31 | Concurrency | 9 |--- |

<!--
- [] Arrays
- [] Two Pointers
- [] Sliding Window
- [] Hash Maps
- [] Sets
- [] Hash-based Lookup Optimisation
- [] Binary Search
- [] Fast Maths
- [] Math-adjacent Optimisation
- [] Dynamic Programming (1D, 2D, State Machines)
- [] Recursion/Backtracking
- [] Heaps
- [] Stacks
- [] Priority Queues
- [] Top-K Problems
- [] Tree Traversal (DFS/BFS)
- [] Bit Manipulation
- [] Numerical Operations
- [] Mixed Hard Problems
- [] Graph Algorithms (Basic BFS/Dijkstra)
- [] Advanced String Parsing / Tries
- [] Timing Constraints
- [] In-memory Optimisation

Array
2197
String
880
Hash Table
825
Math
684
Dynamic Programming
666
Sorting
527
Greedy
470
Depth-First Search
344
Binary Search
343
Database
310
Bit Manipulation
288
Matrix
277
Tree
265
Prefix Sum
263
Breadth-First Search
259
Two Pointers
254
Heap (Priority Queue)
219
Simulation
211
Counting
207
Graph Theory
187
Binary Tree
180
Stack
179
Sliding Window
169
Enumeration
153
Design
136
Backtracking
114
Number Theory
99
Union-Find
99
Linked List
82
Segment Tree
80
Ordered Set
79
Monotonic Stack
73
Divide and Conquer
67
Combinatorics
62
Trie
61
Queue
57
Bitmask
55
Recursion
51
Geometry
46
Binary Indexed Tree
44
Hash Function
43
Memoization
43
Binary Search Tree
43
Shortest Path
41
Topological Sort
40
String Matching
37
Rolling Hash
33
Game Theory
30
Monotonic Queue
25
Interactive
25
Data Stream
24
Brainteaser
21
Doubly-Linked List
15
Merge Sort
15
Randomized
12
Counting Sort
11
Iterator
9
Concurrency
9
Quickselect
8
Suffix Array
8
Sweep Line
8
Probability and Statistics
7
Minimum Spanning Tree
6
Bucket Sort
6
Shell
4
Reservoir Sampling
4
Eulerian Circuit
3
Radix Sort
3
Strongly Connected Component
2
Rejection Sampling
2
Biconnected Component
1
-->

## Environment Setup

- **Host Engine:** VAIO laptop with Polar PGK-114 mechanical keyboard
- **Environment:** headless Ubuntu LTS Virtual Machine via SSH
- **Workspace:** multiplexed via `tmux`
- **Version Control:** verified Git pipeline via custom SSH handshakes
- **Editor/IDE:** Vim

## Progress Summary

| Language | Problems Solved | Algorithms | Last Updated |
|--- |--- |--- |--- |
| **Python** | TBC | TBC | 202607?? |

---

## Notes
1. All code files include inline the problem as well as its Big-O time and space complexity estimations.
2. All codes are built in an isolated local sandbox before deploying to remote trees.
