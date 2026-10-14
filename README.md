# Data Structures & Algorithms (DSA)

<p align="center">
  <strong>Comprehensive Reference Implementations of Fundamental & Advanced Algorithms in C++ and Python</strong>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Language-C++17-18181B?style=for-the-badge&logo=cplusplus&logoColor=white" alt="C++" />
  <img src="https://img.shields.io/badge/Language-Python_3-18181B?style=for-the-badge&logo=python&logoColor=white" alt="Python" />
  <img src="https://img.shields.io/badge/Focus-Interview_Prep_&_Core_CS-18181B?style=for-the-badge" alt="Focus" />
  <img src="https://img.shields.io/badge/License-MIT-18181B?style=for-the-badge" alt="License" />
</p>

---

## Overview

A curated, battle-tested collection of core data structures, graph algorithms, dynamic programming patterns, and mathematical routines. Built to provide clean, self-contained, and performant implementations for technical interviews, competitive programming, and systems engineering foundations.

---

## Tech Stack

<p align="center">
  <img src="https://img.shields.io/badge/C++17-18181B?style=for-the-badge&logo=cplusplus&logoColor=white" alt="C++" />
  <img src="https://img.shields.io/badge/Python_3-18181B?style=for-the-badge&logo=python&logoColor=white" alt="Python" />
  <img src="https://img.shields.io/badge/GCC_/_Clang-18181B?style=for-the-badge&logo=gnu&logoColor=white" alt="GCC" />
  <img src="https://img.shields.io/badge/Git-18181B?style=for-the-badge&logo=git&logoColor=white" alt="Git" />
</p>

---

## Topical Taxonomy

### 1. Trees & Self-Balancing Structures
* **AVL Trees**: Self-balancing binary search trees with left/right rotations and height balancing (`AVL tree.cpp`).
* **Binary Tree Traversals**: Level-order traversal via BFS, max depth, min depth, and max level sums (`leveleordertraversalusingbfs_in_python.py`, `max_depth.cpp`, `max_level_sum_of_a_binary_tree.py`, `maximum_width_tree.py`).

### 2. Graph Algorithms & Traversal
* **Breadth-First Search (BFS)** & **Depth-First Search (DFS)**: Vector-based and matrix adjacency implementations (`BFS and DFS undirected graph(vector implementation).cpp`, `adjacency matrix implementation.cpp`, `bfs_dfs.py`).
* **Shortest Paths**: Unweighted shortest path calculation using BFS queues (`Shortest path algorithm based on BFS.cpp`).
* **Topological Sort**: Directed Acyclic Graph (DAG) scheduling (`topological_sort.cpp`).
* **Hamiltonian Cycles**: Backtracking state evaluation (`count_hamiltonion_cycle.py`).

### 3. Dynamic Programming & Two Pointers
* **Sliding Window**: Longest substring without repeating characters, subarray sums (`sliding_window_longest_substring_without_repeating_characters_without_repeatition.py`, `subarray_sum.py`).
* **Two Pointers & Arrays**: Two Sum II, 3-Sum, Container With Most Water, Sort Colors, Move Zeroes, and Next Permutation (`two_sum II.py`, `three_sum.py`, `container_with_most_water.py`, `sort_colors.py`).
* **Prefix Sums**: 1D and 2D prefix sums for sub-matrix query evaluation (`2Dprefix_sum.py`, `sub_matrix_prefix_sum.cpp`).
* **Dynamic Programming**: Fibonacci state transitions, Maximum Subarray (Kadane's algorithm), Maximum Product Subarray (`fibonacci_problem_on_dp.py_and_linear_way`, `Maximum_sum subarray.py`, `max_product subarray.py`).

### 4. Classical Sorting & Searching
* **Sorting**: Merge Sort, Bubble Sort, Selection Sort, Insertion Sort (`merge_sort.py`, `Mergesort.cpp`, `bubblesort.cpp`, `selectionsort.cpp`, `insertionsort.cpp`).
* **Searching**: Binary Search variants (`Binarysearch.cpp`, `pivot_index.py`).

### 5. Stacks, Queues & Linked Lists
* **Expression Parsing**: Infix to Postfix, Infix to Prefix, Postfix to Infix, Prefix to Infix converters (`infixtopostfix.cpp`, `infixtoprefix.cpp`, `postfixtoinfix.cpp`, `prefixtoinfix.cpp`).
* **Linked Lists**: Node insertion, deletion, merging sorted lists, and reversing in $k$-groups (`linkedlist.cpp`, `Merging_two_linked_list_in_a_sorted_order.cpp`, `reverse_k_groups.cpp`).
* **Queue / Stack Reversal**: Sorting a queue using auxiliary stack structures (`Sorting a queue using stack.cpp`).

### 6. Applied Mathematics & Statistics
* **Statistical Testing**: Chi-square tests and F-tests (`Chi_square_test.py`, `f_test.py`, `t_test.py`).
* **Phonetic Algorithms**: Soundex phonetic encoding implementation (`soundex.py`).

---

## Quickstart

### Compile & Run C++ Implementations
```bash
# Example: Compile AVL Tree
g++ -std=c++17 -O3 "AVL tree.cpp" -o avl_tree
./avl_tree
```

### Execute Python Solutions
```bash
python3 "two_sum II.py"
```

---

## Author

* **Author**: [Prannessh KVA](https://github.com/prannesshkva)
* **Profile**: [GitHub Profile](https://github.com/prannesshkva)

---

## License

This repository is distributed under the MIT License.
