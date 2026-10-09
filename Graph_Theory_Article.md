# Graph Theory: The Hidden Structure Behind Everyday Technology

**Student Name:** Bhaskar Yashwant Hubale

## Introduction

Many systems we use every day look complicated, but their basic structure can often be represented using graphs. In discrete mathematics, a graph is a collection of vertices (nodes) connected by edges (links). Graph theory gives us a simple way to represent relationships, connections, and paths between different objects.

The subject began in 1736, when Leonhard Euler solved the famous Seven Bridges of Königsberg problem by reducing the city's map to points and lines. Nearly three centuries later, the same idea sits behind route planners, social platforms, search engines, and the internet itself. For a student of computer science, graph theory is one of the most useful topics in the Discrete Structures course.

## What Is a Graph?

Consider a social-media network. Each person can be represented by a vertex, while a friendship or connection between two people can be represented by an edge. Similarly, in a road network, cities can be vertices and roads can be edges. Depending on the problem, edges may also have values such as distance, time, or cost. This makes graphs useful for representing both simple and complex relationships.

Formally, a graph is written as G = (V, E), where V is the set of vertices and E is the set of edges. Two vertices joined by an edge are called adjacent, and the degree of a vertex is the number of edges that touch it.

## Types of Graphs

Graphs come in several forms, and choosing the right one is the first step in modelling a problem. In an *undirected graph*, an edge works in both directions, like a Facebook friendship. In a *directed graph*, every edge has a direction, like following someone on Instagram or a hyperlink from one web page to another. A *weighted graph* attaches a number to each edge, such as the distance between two cities. A *tree* is a connected graph with no cycles, and it is used for file systems, organisation charts, and the parse trees built by compilers.

## Key Concepts

A *path* is a sequence of edges that leads from one vertex to another, and a *cycle* is a path that returns to its starting vertex. A graph is *connected* if a path exists between every pair of vertices. Euler paths visit every edge exactly once, while Hamiltonian paths visit every vertex exactly once. Graph colouring assigns colours to vertices so that no two adjacent vertices share a colour, which is the idea behind scheduling exams or assigning radio frequencies without conflicts.

In a computer, a graph is stored either as an *adjacency matrix*, a table of 0s and 1s that shows which vertices are connected, or as an *adjacency list*, which stores the neighbours of every vertex. The list is usually better for sparse graphs because it uses less memory. Two basic traversal methods, Breadth-First Search (BFS) and Depth-First Search (DFS), let a program explore a graph systematically. Dijkstra's algorithm builds on this to find the shortest path in a weighted graph.

## How Graphs Are Used

Graph theory has many practical applications in technology. Google Maps and navigation systems use graph-based models to represent roads and find suitable routes between locations. Computer networks can be represented as graphs where devices are nodes and communication links are edges. This helps in understanding network connectivity and finding efficient paths for data.

Graphs are also important in social networks. Platforms can represent users as vertices and their relationships as edges. By analysing these connections, systems can identify communities, recommend connections, and study how information spreads.

Another important application is web search. Web pages can be considered nodes, while hyperlinks form connections between them. Search technologies can analyse these relationships to understand the structure of the web.

Graphs are equally valuable in cyber security, my own branch of study. Attack graphs show the sequence of steps an intruder could take to move from one machine to another, and network graphs help administrators spot weak links and unusual connections. In compiler design, control-flow graphs and dependency graphs are used to optimise code, and finite automata, which are directed graphs with labelled edges, are used to recognise patterns in text.

## Conclusion

Graph theory is more than a mathematical concept studied in a classroom. It provides a practical language for describing connected systems. From navigation and computer networks to social media and the web, graphs help computers understand relationships and solve problems involving connections and paths. Learning graph theory therefore gives students a foundation for understanding many technologies used in modern computing.
