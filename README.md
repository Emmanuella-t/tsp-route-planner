# Traveling Salesman Problem - Route Optimization 🚚🗺️

This project implements multiple algorithms to solve the classic **Traveling Salesman Problem (TSP)** and evaluates performance, accuracy, and efficiency.

Goal: compare naive, greedy, and dynamic programming solutions while visualizing path optimization.

---

## 🧠 Problem

A traveler must visit all cities in a route **exactly once** and return to the starting point.  
We want the **shortest possible total distance**.

---

## 🧮 Algorithms Implemented

| Algorithm | Approach | Complexity |
|---|---|---|
Brute Force | Try every permutation | O(n!) |
Greedy | Pick nearest city next | O(n²) |
Dynamic Programming (Held-Karp) | DP optimization | O(n² · 2ⁿ) |

---

## 🎯 Purpose
- Demonstrate algorithmic thinking
- Benchmark time & performance
- Show problem-solving + optimization skills

---

## 🛠 Tech Stack
- Python
- Matplotlib (path visualization)
- NetworkX (graph modeling) *(optional)*
- Jupyter Notebook for experiment logs

---

## 📂 Structure

---

## ▶️ To Run (later)
```bash
python src/brute_force.py
python src/greedy.py
python src/dynamic_programming.py
