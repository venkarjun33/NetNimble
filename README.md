# NetNimble

A Python-based solution to minimize network congestion by optimizing routing paths under latency and bandwidth constraints in IIoT environments.

## 📌 Problem Statement

In modern communication networks, especially Industrial Internet of Things (IIoT) systems, it is critical to route data efficiently. This project finds optimal communication paths between network nodes while satisfying constraints like:

- Minimal latency
- Minimum required bandwidth

## 🚀 Key Features

- 🔗 **Graph-Based Network Modeling**: Nodes represent devices and edges signify network links with latency and bandwidth values.
- ✔️ **Path Validation**: Ensures valid, cycle-free paths.
- 📊 **Optimization Logic**: Selects the best path using a cost function that balances latency and bandwidth.
- 🧠 **Custom Heuristics**: Supports α and β tuning to shift between latency vs. bandwidth prioritization.
- 🖼️ **Interactive Visualization**: Visuals of the network and optimal path.
- 🖥️ **Graphical Interface**: GUI built using Tkinter for easy inputs and analysis.

## 🧰 Tech Stack

- **Language**: Python
- **Libraries**:
  - `networkx` – Graph creation and pathfinding
  - `matplotlib` – Network visualization
  - `itertools` – Combinatorial utilities
  - `tkinter` – GUI interface

## 🧠 Algorithm Overview

1. **Graph Construction**: Nodes and edges with weighted latency and bandwidth.
2. **Cost Function**:  
   \[
   \text{Cost} = \alpha \cdot \frac{1}{\text{bandwidth}} + \beta \cdot \text{latency}
   \]
3. **Path Selection**: Finds paths satisfying constraints using Dijkstra’s algorithm.
4. **Output**: Shows the best path, total latency, bandwidth, and cost visually and textually.

## 🖼️ Demo

![image](https://github.com/user-attachments/assets/ca2e89bd-1b82-4808-bb33-302dc15b8841)


## ⚙️ How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/netnimble.git
   cd netnimble
   ```

## 📚 Use Cases
-IIoT Network Simulation
-Routing Optimization Research
-Educational Demonstrations

👤 Author
Venkateshwaran S V


Coimbatore Institute of Technology
