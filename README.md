# Stack Overflow Community Analysis: A Graph-Based Approach

## Overview
This repository contains code for analyzing the Stack Overflow 2018 Developer Survey dataset using graph-based algorithms. The project focuses on constructing a graph to represent developers' interactions on the platform and applying community detection algorithms to identify distinct communities within the Stack Overflow network.

## Introduction/Motivation:
Stack Overflow is a prominent platform for developers worldwide to collaborate, seek solutions, and share knowledge. This project aims to delve into the interactions among developers by analyzing the survey dataset. The primary goal is to utilize graph-based analysis.

The motivation behind this project is to understand the underlying community structures within Stack Overflow and compare the outcomes of different community detection algorithms.
## Model and Problem Statement

### Problem Statement
The project aims to identify the most effective community detection algorithm for revealing meaningful structures within the Stack Overflow community. Key metrics for evaluation include modularity scores, execution times, and the number of communities detected.

### Model
The Stack Overflow Developer Survey data is represented as a graph, where developers are nodes, and relationships are edges. The main objective is to partition nodes into communities using various community detection algorithms.

### Algorithms Used
- Louvain Algorithm: Efficiently organizes communities by maximizing modularity scores.
- Girvan-Newman Algorithm: Hierarchical algorithm that identifies communities by iteratively removing edges with high betweenness centrality.
- Leading Eigenvector Algorithm: Utilizes the leading eigenvector of the modularity matrix to identify well-defined community structures.
- Label Propagation Algorithm: Semi-supervised method that propagates labels through the graph's local structure to identify potential communities.
### Conclusion:
After evaluating the performance of different algorithms, the Label Propagation Algorithm emerges as a suitable choice, striking a balance between modularity and execution time. It offers efficient community detection, especially for large datasets.

## 
This project was developed as part of a course assignment.
