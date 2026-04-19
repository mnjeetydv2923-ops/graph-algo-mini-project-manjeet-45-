# graph-algo-mini-project-manjeet-45-
Implementation of real-world graph algorithms including BFS, DFS, Topological Sorting, Dijkstra, Bellman-Ford, and Minimum Spanning Tree # 🚀 Graph Algorithms Mini Project

## 📌 Overview

This project demonstrates the practical implementation of fundamental **graph algorithms** used in real-world systems such as road networks, social media, and computer networks.

The project covers traversal techniques, shortest path algorithms, dependency resolution, and cost-efficient network design.

---

## 🎯 Objectives

* Represent graphs using **Adjacency Matrix** and **Adjacency List**
* Implement graph traversal algorithms (**BFS** and **DFS**)
* Perform **Topological Sorting** for dependency resolution
* Compute **Shortest Paths** using Dijkstra and Bellman-Ford algorithms
* Construct **Minimum Spanning Trees (MST)** using Prim’s and Kruskal’s algorithms
* Analyze performance using time and memory profiling

---

## 🛠️ Tech Stack

* Python 3.10+
* Jupyter Notebook
* Libraries:

  * matplotlib
  * memory_profiler
  * time
  * (optional) networkx

---

## 📂 Project Structure

```
graph-algo-mini-project-manjeet/
│── README.md
│── requirements.txt
│── .gitignore
│
├── notebooks/
│   └── graph_realworld.ipynb
│
├── images/
│   └── performance_plots.png
│
└── docs/
    └── report.md
```

---

## ⚙️ Setup Instructions

### 1️⃣ Clone Repository

```
git clone https://github.com/your-username/graph-algo-mini-project-manjeet.git
cd graph-algo-mini-project-manjeet
```

### 2️⃣ Create Virtual Environment

```
python -m venv .venv
```

### 3️⃣ Activate Environment

* Windows:

```
.venv\Scripts\activate
```

* Mac/Linux:

```
source .venv/bin/activate
```

### 4️⃣ Install Dependencies

```
pip install -r requirements.txt
```

### 5️⃣ Run Project

```
jupyter lab
```

---

## 📊 Implemented Algorithms

### 🔹 Graph Representation

* Adjacency Matrix
* Adjacency List

### 🔹 Graph Traversal

* Breadth First Search (BFS)
* Depth First Search (DFS)

### 🔹 Topological Sorting

* Used for task scheduling and dependency resolution

### 🔹 Shortest Path Algorithms

* Dijkstra Algorithm (for positive weights)
* Bellman-Ford Algorithm (handles negative weights)

### 🔹 Minimum Spanning Tree (MST)

* Prim’s Algorithm
* Kruskal’s Algorithm

---

## 📈 Performance Analysis

* Time complexity comparison
* Memory usage profiling using `memory_profiler`
* Visualization using `matplotlib`

---

## 📌 Real-World Applications

* Navigation systems (Google Maps)
* Social network analysis
* Project scheduling
* Network design and cabling optimization

---

## 🤔 Reflection

### ✔ Algorithm Suitability

* **Dijkstra** works best for real-time navigation due to efficiency.
* **Bellman-Ford** is useful when negative edges exist.

### ✔ Complexity vs Scalability

* BFS/DFS perform efficiently on sparse graphs.
* Bellman-Ford becomes slower on large graphs due to higher complexity.

### ✔ MST Insights

* **Kruskal** is better for sparse graphs.
* **Prim** performs well for dense graphs.

### ✔ Challenges

* Handling negative weight cycles in Bellman-Ford.
* Choosing correct graph representation for efficiency.

### ✔ Extensibility

* Future work: Implement **A*** algorithm for intelligent pathfinding.

---

## 📦 requirements.txt

```
matplotlib
memory_profiler
jupyterlab
networkx
```

---

## 📚 References

* Introduction to Algorithms – CLRS
* MIT OpenCourseWare (Graph Algorithms)
* NetworkX Documentation: https://networkx.org
* Matplotlib: https://matplotlib.org

---

## 🏁 Final Submission

* Version: `v1.0-submission`
* Contains complete implementation, analysis, and documentation.

---

## 👨‍💻 Author

**Manjeet Yadav**

---


