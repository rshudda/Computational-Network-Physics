# Computational Network Physics — Starter Simulations

**Author:** *Ravishankar Hudda*  
**Website:** https://rshudda.github.io  
**GitHub:** https://github.com/rshudda  

This repository contains a single Jupyter notebook with basic but illustrative simulations in **network science**, aimed at applications in **statistical physics** and **complex systems**.

---

## 📁 Notebook

👉 **Open the notebook:**  
[network_physics_notebook.ipynb](network_physics_notebook.ipynb)

This notebook includes:

1. **Erdős–Rényi Random Graph (G(n, p))**
   - Construction of a random graph with `n` nodes and edge probability `p`
   - Visualization using a spring layout
   - Basic statistics: number of nodes and edges

2. **Degree Distribution**
   - Computation of degree sequence of the random graph
   - Histogram of degree distribution \(P(k)\)
   - Illustration of how random graphs typically have a narrow degree distribution

3. **Watts–Strogatz Small-World Network**
   - Construction of a small-world network with parameters \((n, k, \beta)\)
   - Visualization using a spring layout
   - Comparison with the Erdős–Rényi model

4. **Path Length and Clustering Comparison**
   - Average shortest path length for both networks
   - Average clustering coefficient for both models
   - Demonstration that small-world networks combine:
     - short paths (like random graphs)
     - high clustering (like regular lattices)

5. **Simple SI Spreading Dynamics on Networks**
   - Susceptible–Infected (SI) model on both networks
   - Time evolution of the infected fraction of nodes
   - Comparison of spreading speed on Erdős–Rényi vs small-world topology

---

## 🧠 Purpose

The aim of this notebook is to:

- Build intuition for how **network topology** (random vs small-world) affects:
  - degree distribution
  - distances
  - clustering
  - spreading processes

- Serve as a starting point for more advanced work in:
  - complex networks
  - epidemic spreading
  - synchronization
  - cascading processes

It demonstrates the ability to:
- Translate network models into code
- Use Python tools (`networkx`, `numpy`, `matplotlib`)
- Visualize and interpret basic network observables

---

## 🛠 Requirements

To run the notebook, you need:

- Python 3
- `numpy`
- `matplotlib`
- `networkx`
- `jupyter`

Install with:

```bash
pip install numpy matplotlib networkx jupyter
