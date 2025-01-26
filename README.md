# Mastering Data Structures and Algorithms (DSA)

To tackle Data Structures and Algorithms (DSA) problems effectively, follow these strategies and patterns:

---

## 1. **Understand the Problem**
- **Read the problem statement carefully.**
- **Identify inputs and outputs:** Determine what is provided and what needs to be found.
- **Clarify constraints:** Consider edge cases, size limits, and performance expectations.
- **Ask questions:** If unclear, make assumptions explicit in your solution.

---

## 2. **Choose the Right Data Structure**
- **Array:** For sequential data or when indices are important.
- **HashMap/HashSet:** Fast lookups or uniqueness constraints.
- **Stack/Queue:** For LIFO/FIFO behavior.
- **Heap/Priority Queue:** Quickly access the smallest or largest element.
- **Tree/Graph:** Hierarchical or networked relationships.
- **Linked List:** Dynamic insertions and deletions.
- **Sliding Window:** Subarrays or substrings processing.

---

## 3. **Common Problem-Solving Patterns**

### Two Pointers
- **When to use:** Optimizing space/time complexity in arrays or strings.
- **Examples:** Palindrome checking, merging sorted arrays, finding pairs with a given sum.

### Sliding Window
- **When to use:** Subarray or substring problems.
- **Examples:** Maximum sum of k-length subarray, longest substring without repeating characters.

### Binary Search
- **When to use:** Searching sorted data or optimizing an objective.
- **Examples:** Finding square roots, searching rotated arrays.

### Divide and Conquer
- **When to use:** Problems that can be divided into smaller sub-problems.
- **Examples:** Merge Sort, Maximum subarray sum.

### Backtracking
- **When to use:** Generating all possibilities or solving constraints.
- **Examples:** N-Queens, Sudoku solver.

### Dynamic Programming (DP)
- **When to use:** Problems with overlapping sub-problems.
- **Examples:** Knapsack, Longest Increasing Subsequence.

### Greedy Algorithms
- **When to use:** Local optimization leads to a global solution.
- **Examples:** Interval scheduling, Huffman encoding.

### Graph Traversal
- **BFS:** Shortest path in an unweighted graph.
- **DFS:** Exploring all paths or connected components.
- **Examples:** Maze problems, detecting cycles.

### Union-Find
- **When to use:** Connected components or cycle detection.
- **Examples:** Kruskal’s algorithm.

### Topological Sorting
- **When to use:** Dependency or order-based problems.
- **Examples:** Course schedule, task scheduling.

---

## 4. **Break Down the Problem**
- Write a **high-level plan** for your solution.
- Solve a **simpler version** or focus on a smaller part.
- Create **helper functions** for repetitive tasks.

---

## 5. **Optimize and Analyze**
- **Time complexity:** Is your solution efficient? Can it be improved?
- **Space complexity:** Are there redundant data structures?
- **Test edge cases:** Empty inputs, max/min constraints, duplicates.

---

## 6. **Practice Patterns**
- Solve categorized problems to build pattern recognition.
- Start with easy problems and progress to harder ones.
- Platforms: **LeetCode**, **Codeforces**, **HackerRank**.

---

## 7. **Learn from Mistakes**
- Review your approach after getting stuck or seeing solutions.
- Focus on **why** an algorithm works, not just implementation.

---

## Time Allocation Summary
| **Step**                  | **Time Investment**       |
|---------------------------|---------------------------|
| **Problem Understanding** | 5–10 minutes             |
| **Devising a Strategy**   | 10–15 minutes            |
| **Breaking Down the Problem** | 10–15 minutes        |
| **Writing Pseudocode**    | 10–15 minutes            |
| **Coding and Debugging**  | 20–30 minutes            |
| **Iterative Optimization**| 15–20 minutes            |
| **Process Review**        | 5–10 minutes             |

---

## 10 Dynamic Programming (DP) Patterns

### 1) **1D DP Problems**
- Fibonacci Sequence
- Climbing Stairs
- Coin Change
- House Robber

### 2) **2D DP Problems**
- Grid-based Problems (e.g., Minimum Path Sum)
- Knapsack Problem
- Longest Common Subsequence
- Edit Distance

### 3) **Substring/Subsequence Problems**
- Longest Increasing Subsequence
- Longest Palindromic Substring
- Palindrome Partitioning

### 4) **Partition Problems**
- Partition Equal Subset Sum
- Palindromic Partitioning

### 5) **Game Theory Problems**
- Stone Game
- Nim Game

### 6) **Interval DP Problems**
- Matrix Chain Multiplication
- Burst Balloons

### 7) **Tree DP Problems**
- Binary Tree Maximum Path Sum
- Longest Path in a Tree

### 8) **Bitmask DP Problems**
- Traveling Salesman Problem (TSP)
- Steiner Tree

### 9) **Digit DP**
- Number of Digit One

### 10) **Others**
- Catalan Numbers
- Subset Sum Problem

---

## 10 Graph Patterns

### 1. Graph Traversal
- BFS: **LeetCode 127 - Word Ladder**
- DFS: **LeetCode 200 - Number of Islands**

### 2. Shortest Path
- Dijkstra’s: **LeetCode 743 - Network Delay Time**
- Bellman-Ford: **LeetCode 787 - Cheapest Flights**

### 3. Minimum Spanning Tree (MST)
- Kruskal’s: **LeetCode 1135 - Connecting Cities**
- Prim’s: **LeetCode 1584 - Min Cost**

### 4. Topological Sorting
- Topological Sort: **LeetCode 207 - Course Schedule**
- Kahn’s Algorithm: **LeetCode 210 - Course Schedule II**

### 5. Connected Components
- LeetCode 323 - Number of Connected Components

### 6. Cycle Detection
- LeetCode 207 - Course Schedule

### 7. Graph Coloring
- Bipartite Check: **LeetCode 785**
- M-Coloring: **LeetCode 1042**

### 8. Flow Problems
- Max Flow: **LeetCode 1334**

### 9. Union-Find
- Union-Find: **LeetCode 684**
- Cycle Detection: **LeetCode 261**

### 10. Advanced Graph Problems
- Traveling Salesman Problem (TSP) using Bitmask DP

---

Mastering these strategies, patterns, and techniques will significantly enhance your ability to solve DSA problems confidently.

# Time Complexity of Algorithms

## Arrays (Space-Time Complexity)

| Operation              | Worst Case | Average Case | Best Case |
|------------------------|------------|--------------|-----------|
| Accessing an element   | O(1)       | O(1)         | O(1)      |
| Updating an element    | O(1)       | O(1)         | O(1)      |
| Deleting an element    | O(n)       | O(n)         | O(1)      |
| Inserting an element   | O(n)       | O(n)         | O(1)      |
| Searching for an element | O(n)     | O(n)         | O(1)      |

---

## Algorithm Complexity

### Sorting Algorithms

| Algorithm      | Worst Case    | Average Case | Best Case     | Space Complexity |
|----------------|---------------|--------------|---------------|-------------------|
| Quicksort      | O(n²)         | O(n log n)   | O(n log n)    | O(log n)         |
| Mergesort      | O(n log n)    | O(n log n)   | O(n log n)    | O(n)             |
| Heapsort       | O(n log n)    | O(n log n)   | O(n log n)    | O(1)             |
| Bubble Sort    | O(n²)         | O(n²)        | O(n)          | O(1)             |
| Insertion Sort | O(n²)         | O(n²)        | O(n)          | O(1)             |
| Selection Sort | O(n²)         | O(n²)        | O(n²)         | O(1)             |

---

### Searching Algorithms

| Algorithm          | Worst Case    | Average Case | Best Case     | Space Complexity |
|--------------------|---------------|--------------|---------------|-------------------|
| Binary Search      | O(log n)      | O(log n)     | O(1)          | O(1)             |
| Linear Search      | O(n)          | O(n)         | O(1)          | O(1)             |

---

## Strings (Space-Time Complexity)

| Operation         | Worst Case     | Average Case  | Best Case      |
|-------------------|----------------|---------------|----------------|
| Accessing         | O(1)          | O(1)          | O(1)           |
| Deleting          | O(n)          | O(n)          | O(1)           |
| Inserting         | O(n)          | O(n)          | O(1)           |
| Searching         | O(n * m)      | O(n)          | O(1)           |
| Slicing           | O(n)          | O(n)          | O(n)           |
| Concatenating     | O(n + m)      | O(n + m)      | O(n)           |
| Comparison        | O(n)          | O(n)          | O(n)           |

---

### String Search Algorithms

| Algorithm               | Worst Case        | Average Case    | Best Case    | Space Complexity |
|-------------------------|-------------------|-----------------|-------------|-------------------|
| Radix Sort (m = length) | O(n * m)         | O(n * m)        | O(n * m)    | O(n + m)         |
| Naive Search            | O(m * (n - m + 1)) | O(n * m)      | O(n)        | O(1)             |
| Knuth-Morris-Pratt      | O(m + n)         | O(n)            | O(n)        | O(m)             |
| Boyer-Moore             | O(n * m)         | O(n)            | O(n/m)      | O(m)             |
| Rabin-Karp              | O(m * (n - m + 1)) | O(n + m)      | O(m)        | O(m)             |

---

## Linked Lists (Space-Time Complexity)

| Operation              | Worst Case | Average Case | Best Case |
|------------------------|------------|--------------|-----------|
| Accessing             | O(n)       | O(n)         | O(1)      |
| Deleting (after search) | O(1)     | O(1)         | O(1)      |
| Inserting (after search) | O(1)   | O(1)         | O(1)      |
| Searching              | O(n)       | O(n)         | O(1)      |
| Traversing             | O(n)       | O(n)         | O(n)      |

---

## Trees (Space-Time Complexity)

| Operation            | Worst Case | Average Case | Best Case | Space Complexity |
|----------------------|------------|--------------|-----------|-------------------|
| Depth-First Search   | O(n)       | O(n)         | O(n)      | O(n)             |
| Breadth-First Search | O(n)       | O(n)         | O(n)      | O(n)             |
| Tree Sort            | O(n²)      | O(n log n)   | O(n log n) | O(n)            |

---

## Graphs (Space-Time Complexity)

| Algorithm               | Time Complexity    | Space Complexity |
|-------------------------|--------------------|-------------------|
| Breadth-First Search    | O(V + E)          | O(V)             |
| Depth-First Search      | O(V + E)          | O(V)             |
| A* Search               | O(E)              | O(V)             |
| Dijkstra’s Algorithm    | O(V²) / O(E log V)| O(V)             |

---

## Heaps (Space-Time Complexity)

| Operation       | Worst Case | Average Case | Best Case |
|-----------------|------------|--------------|-----------|
| Insert          | O(log n)   | O(log n)     | O(1)      |
| Delete          | O(log n)   | O(log n)     | O(1)      |
| Find Min/Max    | O(1)       | O(1)         | O(1)      |
| Search          | O(n)       | O(n)         | O(1)      |

