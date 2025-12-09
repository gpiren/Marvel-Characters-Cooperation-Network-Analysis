# Marvel Character Partnerships Network Analysis

Social Network Analysis of Marvel Universe character partnerships using R and igraph.

## Overview

This project analyzes the Marvel character partnerships network (2018) containing 350 characters and 346 partnerships. We examine network structure, community detection, and centrality measures to understand relationships between heroes, villains, and neutral characters.

## Dataset

- **Source:** [Marvel Partnerships Network (2018)](https://networks.skewed.de/net/marvel_partnerships)
- **Nodes:** 350 Marvel characters
- **Edges:** 346 partnerships
- **Node Categories:** Heroes, Villains, Neutral

## Key Findings

- **Average Degree:** ~2 partnerships per character
- **Clustering Coefficient:** 0.22 (moderately clustered)
- **Assortativity:** -0.01 (nearly random connectivity)
- **Modularity:** 0.91 (strong community structure detected via Louvain method)
- **Most Central Character:** Venom (by harmonic centrality)

## Methods used

- **R** with igraph, ggplot2, dplyr, tidygraph
- **Community Detection:** Louvain algorithm
- **Centrality Measures:** PageRank, Closeness, Betweenness, Harmonic

## Files

- `marvel_network.rda` - Network object
- `data/nodes.csv` - Character nodes
- `data/edges.csv` - Partnership edges
- Main analysis in Quarto document

## Authors

Aurora Sterpellone & Gür Piren
