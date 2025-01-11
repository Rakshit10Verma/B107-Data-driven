# Facebook Network Analysis Project

## Overview
This project analyzes Facebook's social network structure using user profiles, friendship groupings (Circles), and ego networks. The analysis employs Python's NetworkX library to understand patterns and factors influencing the formation of socially cohesive communities.

## Research Question
Can analysis of user profile, friendship groupings (Circles), and ego network on Facebook reveal underlying patterns and factors that influence the formation and composition of socially cohesive communities?

## Dependencies
- NetworkX
- Pandas
- Matplotlib
- NumPy
- Requests

## Dataset
The project uses the `facebook_combined.txt` dataset, which contains network structure data of Facebook connections.

## Key Features
1. **Network Construction**
   - Builds network graph using NetworkX
   - Visualizes friend lists and connections
   - Analyzes largest connected components

2. **Network Analysis**
   - Degree distribution analysis
   - Connected component analysis
   - Path length calculations
   - Centrality measures
   - Clustering coefficient analysis
   - Network density calculations

3. **Comparative Analysis**
   Compares the Facebook network with three theoretical network models:
   - Erdős-Rényi (ER) Model
   - Watts-Strogatz (WS) Model
   - Barabási-Albert (BA) Model

## Key Findings
- Network Size: 4,039 nodes and 88,234 edges
- Average Shortest Path Length: 3.69
- Clustering Coefficient: 0.60
- Network Density: 0.10
- Heterogeneous connectivity patterns
- Single weakly connected component indicating high cohesion
- Moderate level of local clustering

## Usage
1. Import required libraries
2. Load the Facebook combined dataset
3. Run network construction and analysis functions
4. Generate visualizations and metrics
5. Compare with theoretical network models

## Results
The analysis reveals:
- A large, well-connected network
- Heterogeneous degree distribution
- Efficient information flow
- Moderate local clustering
- Sparse overall network structure
- Presence of influential users with high connectivity

## Future Work
- Deeper analysis of centrality measures
- Temporal analysis of network evolution
- Community detection algorithms
- User attribute correlation studies
- Influence propagation analysis

## Author
Rakshit Verma (Student Number: GH1023768)

## Academic Context
This project was submitted as part of the Data Driven Strategic Decision Making module (B107) at GISMA Business School, University of Applied Sciences.
