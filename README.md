# Stack Overflow Tag Network Analysis

This project visualizes the relationships between Stack Overflow tags using **Network Analysis** techniques.  
Tags are represented as nodes, and their co-occurrence relationships are modeled as weighted edges.

## 📌 Project Overview

- Stack Overflow tags are modeled as a graph using **NetworkX**
- Node size represents tag popularity
- Colors indicate different tag groups
- Isolated and weakly connected nodes (outliers) are removed
- Visualization is generated using a force-directed (spring) layout

## 🧠 Methodology

1. Nodes and edges are loaded from CSV files
2. A graph structure is created using NetworkX
3. The largest connected component is extracted to remove outliers
4. Spring layout is applied for better spatial distribution
5. The final network is visualized using Matplotlib

## 📊 Visualization Result

Below is the final network graph after cleaning outliers and optimizing layout parameters:

![Stack Overflow Network](stackoverflow_network_clean.png)

## 🛠 Technologies Used

- Python
- NetworkX
- Pandas
- Matplotlib
- NumPy
