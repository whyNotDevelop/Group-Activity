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

