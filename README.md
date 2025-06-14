# Human Brain Connectome Analysis - Lab 1

This repository contains the code and analysis conducted during Laboratory Work 1 for studying the **human brain connectome**, inspired by the [Human Connectome Project](https://www.humanconnectome.org/). The work focuses on understanding the structure and characteristics of the brain graph using various **network science techniques**.

---

## 📊 Dataset Overview

The dataset represents a structural connectome of the human brain at different resolutions.  
Each node corresponds to a brain area, and each edge represents a structural connection between two areas of the brain.

---

##  Tools and Libraries Used

- Python 3
- `networkx` – for graph modeling and analysis
- `numpy` and `scipy` – for numerical computations
- `seaborn` and `matplotlib` – for static data visualization
- `plotly` – for interactive graph visualization
- `collections`, `os`, and `typing` – for data handling

---

## Problem Breakdown and Analysis

### Problem 0 – How to Plot the Connectome

- Learned how to visualize the connectome using NetworkX and Plotly.
- Generated aesthetically clear layouts using force-directed algorithms.

### Problem 1 – Graph Analysis 

#### 1.1 Main Characteristics of the Graph
- Number of nodes, number of edges
- Average degree
- Graph density
- Clustering coefficient

#### 1.2 Path Length
- Average shortest path length
- Diameter of the graph

#### 1.3 Degree Distribution
- Plotted the histogram of node degrees
- Interpreted scale-free nature

#### 1.4 Most Important Neurons (Nodes)
- Calculated and ranked nodes by:
  - Degree centrality
  - Betweenness centrality
  - Closeness centrality
- Analyzed overlap between top nodes in all three metrics

#### 1.5 Is the Brain a Complex Network?
- Answered using small-world characteristics:
  - High clustering
  - Short path lengths



### Problem 2 – Labeling the Brain Connectome 

- Mapped each brain region to a cognitive function using a predefined dictionary
- Analyzed how structural centrality aligns with functional importance



### Problem 3 – Assortativity 

- Computed assortativity coefficients:
  - By degree
  - By anatomical label
- Interpreted the implications on brain modularity



### Problem 4 – Transcranial Magnetic Stimulation 

- Simulated how applying stimulation to specific areas might impact the rest of the network
- Highlighted most sensitive and highly connected brain areas



## Summary of Analysis Performed

- Graph construction and visualization
- Statistical analysis of graph structure
- Centrality and importance metrics
- Functional labeling of brain regions
- Community and modularity analysis
- Assortativity (similarity) in node connections
- Graph-based simulation of external stimulation



## Sample Visualizations

- Force-directed layout showing connectome
- Top 10 nodes by degree, closeness, and betweenness
- Histograms of degrees and path lengths
- Interactive community-colored graphs (Plotly)




