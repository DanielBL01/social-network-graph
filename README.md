# Social Network Graph

A Social Network can be represented as a Graph where vertices represent users and edges represent connections i.e. friends 

This project is to learn about Graphs and Graph Traversals while representing a Social Network in order to see the results of different traversals
in the Network

## About Graphs
Graphs can either be directed or undirected. Similar to singly and doubly lists, a directed edge is a one way street and a undirected edge is a two way street.

## Graphs Representations 
There are two ways to represent Graphs.

1. Adjacency List
2. Adjacency Matrices

## Graph Traversals
The common Graph Traversals to know are

1. DFS
2. BFS
3. Dijkstra's Shortest Path Algorithm
4. Minimum Spanning Tree

## Graph Terms
### Directed Graph
- **Outdegree**: Total number of vertices leaving
- **Indegree**: Total number of vertices entering
- **Total Degree**: Summation of Outdegree and Indegree
- **Source**: A vertex with Indegree of zero denoted as *u*
- **Sink**: A vertex with Outdegree of zero denoted as *v*
- **Path**: A sequence of verticies [v0, v1, ..., vn-1] where v0 = *u* (source) and vn-1 = *v* (sink)
- **Length**: n - 1 (Intuitively, the length of a path is the number of edges it traverses)

**Note**: The sequence in a path may consist of a single vertex

**Note**: If there exists a path from *u* to *v*, then *v* is said to be *reachable* from *u*

Graphs are often decorated by adding...
- Lengths to edges
- Weights to vertices
- Defining a Start vertex

### Directed Acyclic Graph (DAG)
DAG is a directed graph which has no *cycles* which are paths that contain one or more edges and which begin and end at the same vertex.
- **Sources**: Verticies in DAG which have no incoming edges
- **Sinks**: Verticies in DAG which have no outgoing edges
- **Topological Ordering**: Ordering of the verticies in which each edge if from a vertex earlier in the ordering to a vertex later in the ordering. 

### Undirected Graph
Finish Later