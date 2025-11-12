# Graph Algorithms in Real-Life Applications

**Course:** Design and Analysis of Algorithms Lab  
**Instructor:** Dr. Aarti  
**Name:** Anshika Goyal
**Enrollment No.:** 2301201177

---

## Overview

This project demonstrates how fundamental graph traversal and optimization algorithms can be used to solve real-world problems. Four graph algorithms—BFS/DFS, Bellman-Ford, Dijkstra's, and Minimum Spanning Tree (MST)—are implemented to model practical scenarios such as social network friend suggestions, navigation systems, disaster response routing, and IT infrastructure cost minimization.

---

## Table of Contents

- [Overview](#overview)
- [Technology Stack](#technology-stack)
- [Problems and Algorithms](#problems-and-algorithms)
  - [Problem 1: Social Network Friend Suggestion (BFS/DFS)](#problem-1-social-network-friend-suggestion-bfsdfs)
  - [Problem 2: Route Finding (Bellman-Ford)](#problem-2-route-finding-bellman-ford)
  - [Problem 3: Emergency Routing (Dijkstra's)](#problem-3-emergency-routing-dijkstras)
  - [Problem 4: Network Cable Installation (MST)](#problem-4-network-cable-installation-mst)
- [Profiling and Visualization](#profiling-and-visualization)
- [How to Run](#how-to-run)
- [References](#references)

---

## Technology Stack

- Python 3.8+
- Jupyter/Colab notebooks
- Libraries: `collections`, `heapq`, `matplotlib`, `memory_profiler`

---

## Problems and Algorithms

### Problem 1: Social Network Friend Suggestion (BFS/DFS)
- **Algorithm:** Breadth-First Search (BFS) or Depth-First Search (DFS).
- **Objective:** Suggest new friends for a user based on mutual connections in an undirected graph model of users and friendships.
- **Application Domain:** Social Media (e.g., Facebook, LinkedIn).

### Problem 2: Route Finding (Bellman-Ford)
- **Algorithm:** Bellman-Ford.
- **Objective:** Find shortest paths from a source to all nodes, including graphs with negative edge weights.
- **Application Domain:** Navigation systems (e.g., Google Maps).

### Problem 3: Emergency Routing (Dijkstra's)
- **Algorithm:** Dijkstra's Algorithm.
- **Objective:** Determine the fastest emergency response routes in a city network with all positive edge weights.
- **Application Domain:** Disaster response/management.

### Problem 4: Network Cable Installation (MST using Prim/Kruskal)
- **Algorithm:** Minimum Spanning Tree (Prim's or Kruskal’s algorithm).
- **Objective:** Connect all offices with minimum total cable cost.
- **Application Domain:** IT Infrastructure and Telecom.

---

## Profiling and Visualization

- Each algorithm’s runtime and memory consumption can be profiled with Python’s `time` and `memory_profiler` modules.
- Visualization of execution time versus graph size is provided via `matplotlib` (optional but awarded marks).

---

## How to Run

1. Clone the repository:  
   `git clone <your-github-repo-url>`
2. Navigate to the notebook and open `graphrealworld.ipynb`.
3. Install dependencies:  
   `pip install -r requirements.txt`
4. Run cells to see solutions, complexity analysis, and sample outputs.

---

