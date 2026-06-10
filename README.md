# Solve-DSA-Java

A professional, structured repository containing Java solutions for LeetCode and standard Data Structures & Algorithms (DSA) problems. The repository is organized as a phase-based roadmap designed for technical interview preparation, resumes, and portfolios.

## Progress Tracker

| Phase | Completed | Total | Progress |
|---|---|---|---|
| **Phase 1 Arrays Strings Hashing** | 31 | 35 | █████████░ 88.6% |
| **Phase 2 Two Pointers Sliding Window** | 14 | 14 | ██████████ 100.0% |
| **Phase 3 Stack Queue** | 1 | 5 | ██░░░░░░░░ 20.0% |
| **Phase 4 Trees** | 10 | 15 | ███████░░░ 66.7% |
| **Phase 5 Graphs** | 0 | 10 | ░░░░░░░░░░ 0.0% |
| **Phase 6 Dynamic Programming** | 14 | 20 | ███████░░░ 70.0% |

## Phase Roadmap & Folder Structure

### Phase 1: Arrays, Strings & Hashing
Fundamental data structures and operations.
- **Arrays**: Linear traversal, prefix/suffix products, Kadane's algorithm, and custom problems.
- **Strings**: Anagrams, custom counts, and grouping.
- **HashMap / HashSet**: Unique tracking and fast lookups.
- **Prefix Sum**: Subarray product/sum optimizations.
- **Math & Simulation**: Mathematical sequences and simulations.
- **Sorting**: Sorting algorithms and custom comparator implementations.

### Phase 2: Two Pointers & Sliding Window
Optimizing nested loops to linear or log-linear operations.
- **Two Pointers**: Traversing from both ends, fast & slow pointers.
- **Sliding Window**: Subarrays and circular constraints.
- **Binary Search**: Searching sorted constraints.

### Phase 3: Stack & Queue
Linear data structures with LIFO and FIFO properties.
- **Stack**: Collision simulations and matching brackets.

### Phase 4: Linked Lists & Trees
Non-contiguous linear and hierarchical structures.
- **Linked List**: List reversal, node partitioning, cycle detection, and list sums.
- **Trees**: Binary Tree DFS traversals and tree sum operations.
- **Heap**: PriorityQueue and Top-K frequent elements.

### Phase 5: Graphs (Future Expansion)
Advanced node networks.
- *Status: Prepared folder structure for BFS, DFS, Union-Find, and Topological Sort.*

### Phase 6: Dynamic Programming & Advanced Topics
Optimized recursion and bit manipulations.
- **Dynamic Programming**: Subproblem optimization and digit DP.
- **Greedy**: Sorting-based greedy selections.
- **Backtracking**: Happy string generation, balanced parenthesis backtracking.
- **Bit Manipulation**: Alternating bits, complement masks, carry simulations.

---

## Complexity Reference Guide

| Complexity | Notation | Description | Example Algorithm |
|---|---|---|---|
| **Constant** | `O(1)` | Runs in fixed time regardless of inputs | Bitwise operations |
| **Logarithmic** | `O(log N)` | Input size halves at each step | Binary Search |
| **Linear** | `O(N)` | Traverses input elements once | Single pass array traverse |
| **Linearithmic** | `O(N log N)` | Divide and conquer sorting | Merge Sort / Quick Sort |
| **Quadratic** | `O(N^2)` | Nested loops over input size | Bubble Sort / Matrix traversals |
| **Exponential** | `O(2^N)` | Branching recursion processes | Generating happy strings |

---

## How to Contribute

To add a new LeetCode solution to this roadmap:
1. Identify the correct Phase and subfolder (e.g. `Phase-1-Arrays-Strings-Hashing/HashMap/`).
2. Add your solution in a file named exactly as written in LeetCode (e.g., `Leetcode 1 ∶ Two Sum`, with no extension unless standard).
3. Verify the file compiles and update the Progress Tracker in this README.

---

## Technical Specifications
- **Java Version**: SE 17+
- **Coding Style**: Clean Java syntax with descriptive comments and multi-approach separation.
