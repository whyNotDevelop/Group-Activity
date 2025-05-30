# Group Activity: Shortest Path Finder

[![Python](https://img.shields.io/badge/Python-3.x-blue?style=for-the-badge&logo=python)](https://www.python.org/)  
[![GitHub Repo Size](https://img.shields.io/github/repo-size/whyNotDevelop/Group-Activity?style=flat)](https://github.com/whyNotDevelop/Group-Activity)  

---

## 👥 Team Members

- Akhona Dlamini (22363064)  
- Kwanele Sishi (22315536)  
- Sicelo Thusi (21907372)  

---

## 📖 Overview

This Python script demonstrates **Dijkstra’s Algorithm** to find the shortest path between two cities in a weighted graph. We use a greedy approach followed by a priority-queue implementation to compare results.

---

## 🔑 Key Features

1. **Step-by-step greedy approach**  
   - Manually tracks costs from source (`DBN`) → destination (`JHB`).  
   - Shows intermediate calculations and chosen vertices.  

2. **Dijkstra’s Algorithm implementation**  
   - Uses `heapq` for an efficient priority queue.  
   - Computes shortest distances to all nodes and reconstructs the optimal path.

3. **Graph Representation**  
   - Adjacency dictionary: `{ node: { neighbor: weight, … } }`.  
   - Easily extensible to more locations or different edge weights.

---

## 📂 Repository Structure
Group-Activity/
├─ ShortestPath.png # Visual diagram of the graph
└─ shortest_path.py # Dijkstra’s Algorithm implementation & greedy demo


---

## 🚀 Getting Started

1. **Clone the repo**  
   ```bash
   git clone https://github.com/whyNotDevelop/Group-Activity.git
   cd Group-Activity
2. Install dependencies
No external libraries required beyond the Python standard library.

3. Run the script
   ```bash
   python shortest_path.py

## 🧩 How It Works
Greedy Walkthrough:

Initialize source cost (DBN) = 0, others = ∞.

At each step, pick the unvisited node with the smallest cost.

Update neighbor costs and mark nodes as visited.

Repeat until the destination is reached.

Dijkstra Function:

dijkstra(graph, start): returns (distances, previous_nodes).

reconstruct_path(prev, start, end): builds the path list from start to end.

## 📜 Example Output
```bash
Shortest distances: {'DBN': 0, 'PMB': 89, 'RBY': 112, 'HMT': 212, 'VRT': 218, 'JHB': 324}
Shortest path from DBN to JHB: ['DBN', 'RBY', 'VRT', 'JHB']


