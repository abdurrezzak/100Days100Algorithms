---
layout: post
title: "Day-25: Floyd-Warshall All Pairs Shortest Path ALgorithm"
img: rsz_25floydwarshall.jpg # Add image post (optional)
date: 2017-11-12 12:54:00 +0300
description: 
tag: [Dynamic]
---

Floyd-Warshall is a shortest path algorithm just like Dijkstra and Bellman Ford. However, it computes the shortest paths between each and every one of the pairs in a weighted graph. 

It works on non-negative weighted graphs.

The algorithm is very straightforward. 

It takes a graph as an adjacency matrix and iterates through every possible triplets of vertices.

If including a node in a path is reasonable, it takes it. If not, it does not.

The recurrence relation looks like this: 

    *d[u][v] = min(d[u][x] + d[x][v], d[u][v])*


Time complexity: *O(V^3)* 

Here is the link of my C++ implementation of Floyd-Warshall Algorithm: [Floyd-Warshall Algorithm](https://github.com/abdurrezzak/100-Days-100-Algorithms-/blob/master/25.FloydWarshall.cpp)
