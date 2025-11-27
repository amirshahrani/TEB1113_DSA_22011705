# TEB1113 - Algorithm & Data Structure

Lab exercises and project for Algorithm & Data Structure course (May 2025). This repository contains implementations of fundamental data structures and algorithms in C++, progressing from basic concepts to advanced graph traversal techniques.

## 📁 Repository Structure

```
├── L1/                    # Introduction
├── L2/                    # Algorithm Challenges
├── L3/                    # Linked Lists
├── L4/                    # Circular Linked Lists
├── L5/                    # Stack
├── L6/                    # Queue Implementations
├── L7/                    # Binary Tree
├── L8/                    # BST & Heap
├── L9/                    # Graph Traversal
└── Project/               # AlgoSeek Web App
```

## 🔬 Lab Exercises

| Lab | Topic                   | Files                                                                                                   |
| --- | ----------------------- | ------------------------------------------------------------------------------------------------------- |
| 1   | Introduction to Structs | [Intro](./L1/Intro.cpp)                                                                                 |
| 2   | Matrix Algorithms       | [Easy](./L2/Easy.cpp) • [Medium](./L2/Medium.cpp) • [Hard](./L2/Hard.cpp)                               |
| 3   | Linked Lists            | [Singly](./L3/Singly.cpp) • [Doubly](./L3/Doubly.cpp)                                                   |
| 4   | Circular Linked Lists   | [Circular Singly](./L4/CircularSingly.cpp) • [Circular Doubly](./L4/CircularDoubly.cpp)                 |
| 5   | Stack                   | [Stack](./L5/Stack.cpp)                                                                                 |
| 6   | Queue                   | [Queue](./L6/Queue.cpp) • [Circular Queue](./L6/CircularQueue.cpp) • [Array Queue](./L6/ArrayQueue.cpp) |
| 7   | Binary Tree             | [BinaryTree](./L7/BinaryTree.cpp)                                                                       |
| 8   | BST & Heap              | [BST](./L8/BinarySearchTree.cpp) • [Heap](./L8/Heap.cpp)                                                |
| 9   | Graph Traversal         | [BFS](./L9/BreadthFirstSearch.cpp) • [DFS](./L9/DepthFirstSearch.cpp)                                   |

## 📚 Topics Covered

### Data Structures

- **Linear**: Arrays, Linked Lists (Singly, Doubly, Circular), Stacks, Queues
- **Non-Linear**: Binary Trees, Binary Search Trees, Heaps

### Algorithms

- Matrix operations (diagonal sums, rotation, boolean matrix)
- Tree traversals (In-order, Level-order)
- Graph traversals (BFS, DFS)
- Heapify operations (Min/Max)

## 🚀 Getting Started

### Prerequisites

- C++ compiler (g++, clang++, or MSVC)

### Compilation

```bash
# Example: Compile and run Stack implementation
g++ L5/Stack.cpp -o stack
./stack
```

## 🎯 Course Project

### [AlgoSeek](./Project) - Search Algorithm Visualizer

An interactive web application to visualize and compare Linear and Binary Search algorithms.

**🌐 Live Demo:** [algoseek.pages.dev](https://algoseek.pages.dev)

**Features:**

- Step-by-step algorithm visualization
- Customizable input data
- Performance metrics comparison
- Best/worst case scenario testing
