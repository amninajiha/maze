# 🌀 Maze Generator & Solver

&gt; Self-directed project built to understand core computer science concepts through implementation. No frameworks, no libraries—just algorithms and math.

**[🎮 Live Demo](https://amninajiha.github.io/maze/)** · **[📁 Repository](https://github.com/amninajiha/maze)**

---

## ✨ What It Does

- **Generates** perfect mazes using the **Recursive Backtracker** (Randomized DFS) algorithm
- **Solves** them with **Breadth-First Search (BFS)** to find the shortest path
- **Visualizes** both algorithms executing step-by-step in real-time on an HTML5 Canvas

---

## 🧠 Core Concepts

| Concept | Implementation |
|--------|----------------|
| **Graph Traversal** | Each cell is a node; open passages define edges |
| **Stack Logic** | Explicit stack manages backtracking during generation |
| **Queue Logic** | FIFO queue explores nodes level-by-level for BFS |
| **Backtracking** | Recursive exploration with path unwinding when hitting dead ends |
| **Shortest Path** | BFS guarantees optimal path in unweighted grid graphs |

---

## 🛠️ Built With

- **Vanilla JavaScript** — Algorithm logic and state management
- **HTML5 Canvas** — Pixel-perfect rendering and animation loop
- **CSS** — Clean UI styling and responsive layout

---

## 🚀 Quick Start

No build tools. No dependencies. Just open and run.

```bash
# Clone the repository
git clone https://github.com/amninajiha/maze.git

# Navigate to the project
cd maze

# Open in any modern browser
open index.html
