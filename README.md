# ⚡ Algorithm Mastery

> A comprehensive collection of algorithm chapters with **visual explanations**, **step-by-step diagrams**, and complete implementations in **Java**, **Python**, and **C++**.

Built from insights across classic computer science texts including *Introduction to Algorithms* (CLRS), *Grokking Algorithms*, *The Algorithm Design Manual*, *Cracking the Coding Interview*, and more.

---

## 📚 Chapters

| # | Algorithm | Category | Complexity |
|---|-----------|----------|------------|
| 1 | [**Binary Search**](chapters/01-binary-search.md) | Searching | O(log n) |
| 2 | [**Selection Sort**](chapters/02-selection-sort.md) | Sorting | O(n²) |
| 3 | [**Merge Sort**](chapters/03-merge-sort.md) | Sorting (Divide & Conquer) | O(n log n) |
| 4 | [**Quicksort**](chapters/04-quicksort.md) | Sorting (Divide & Conquer) | O(n log n) avg |
| 5 | [**Breadth-First Search**](chapters/05-bfs.md) | Graph Traversal | O(V + E) |
| 6 | [**Dijkstra's Algorithm**](chapters/06-dijkstra.md) | Shortest Path | O((V+E) log V) |
| 7 | [**Dynamic Programming (Knapsack)**](chapters/07-dynamic-programming.md) | Optimization | O(n × W) |
| 8 | [**Hash Tables**](chapters/08-hash-tables.md) | Data Structures | O(1) avg |
| 9 | [**Depth-First Search**](chapters/09-dfs.md) | Graph Traversal | O(V + E) |
| 10 | [**Hungarian Algorithm**](chapters/10-hungarian-algorithm.md) | Assignment / Matching | O(n³) |
| 11 | [**Greedy Algorithms**](chapters/11-greedy-algorithms.md) | Optimization Strategy | O(n log n) |
| 12 | [**Heapsort**](chapters/12-heapsort.md) | Sorting | O(n log n) |
| 13 | [**Topological Sort**](chapters/13-topological-sort.md) | Graph Ordering | O(V + E) |
| 14 | [**K-Nearest Neighbors**](chapters/14-knn.md) | Machine Learning | O(n × d) |
| 15 | [**A* Search**](chapters/15-a-star-search.md) | Pathfinding | O(E log V) |

---

## 🗺️ Learning Path

```
                    ┌─────────────────┐
                    │  Binary Search  │ ← Start here
                    │    (Ch. 1)      │
                    └────────┬────────┘
                             │
              ┌──────────────┼──────────────┐
              ▼              ▼              ▼
      ┌──────────────┐ ┌──────────┐ ┌──────────────┐
      │Selection Sort│ │Hash Table│ │    BFS       │
      │   (Ch. 2)    │ │ (Ch. 8)  │ │   (Ch. 5)    │
      └──────┬───────┘ └──────────┘ └──────┬───────┘
             │                              │
      ┌──────┴───────┐              ┌──────┴───────┐
      ▼              ▼              ▼              ▼
┌──────────┐  ┌──────────┐  ┌──────────┐  ┌──────────┐
│Merge Sort│  │ Quicksort│  │   DFS    │  │ Dijkstra │
│ (Ch. 3)  │  │  (Ch. 4) │  │ (Ch. 9)  │  │ (Ch. 6)  │
└─────┬────┘  └──────────┘  └─────┬────┘  └─────┬────┘
      │                           │              │
      ▼                    ┌──────┴──────┐ ┌─────┴─────┐
┌──────────┐               ▼             ▼ ▼           ▼
│ Heapsort │        ┌───────────┐  ┌───────────┐ ┌──────────┐
│ (Ch. 12) │        │Topological│  │ A* Search │ │ Hungarian│
└──────────┘        │   Sort    │  │ (Ch. 15)  │ │ Algorithm│
                    │ (Ch. 13)  │  └───────────┘ │ (Ch. 10) │
                    └───────────┘                └──────────┘
                           │
              ┌────────────┼────────────┐
              ▼            ▼            ▼
       ┌───────────┐ ┌───────────┐ ┌─────────┐
       │ Dynamic   │ │  Greedy   │ │  KNN    │
       │Programming│ │Algorithms │ │(Ch. 14) │
       │  (Ch. 7)  │ │ (Ch. 11)  │ └─────────┘
       └───────────┘ └───────────┘
```

---

## 📖 Each Chapter Includes

- 🎨 **Realistic hero image** — a visual metaphor for the algorithm
- 📊 **Step-by-step diagram** — visual walkthrough of the algorithm execution
- 📝 **Clear explanation** — how it works, when to use it, complexity analysis
- 💻 **Three implementations** — Java, Python, and C++ with comments
- 🔗 **Navigation links** — chapters link to each other sequentially

---

## 📚 Source Material

These chapters synthesize content from:

| Book | Author(s) | Key Topics |
|------|-----------|------------|
| *Introduction to Algorithms* (CLRS) | Cormen, Leiserson, Rivest, Stein | Formal analysis, all algorithms |
| *Grokking Algorithms* | Aditya Y. Bhargava | Visual explanations, intuitive approach |
| *The Algorithm Design Manual* | Steven S. Skiena | Practical applications, war stories |
| *A Common-Sense Guide to DSA* | Jay Wengrow | Beginner-friendly explanations |
| *Cracking the Coding Interview* | Gayle Laakmann McDowell | Interview-oriented problems |
| *Advanced Algorithms and Data Structures* | Marcello La Rocca | Advanced topics, pathfinding |
| *Algorithms and Data Structures for Massive Datasets* | Medjedovic, Tahirovic | Scalability patterns |
| Hungarian Algorithm Papers | Various | Assignment problem specifics |

---

## 🚀 Quick Start

Pick any chapter from the table above, or start with [Chapter 1: Binary Search](chapters/01-binary-search.md) for a gentle introduction.

Each code implementation is **self-contained** and can be copied directly into your IDE to compile and run.

---

*Built with ⚡ by synthesizing classic algorithm textbooks into practical, visual guides.*
