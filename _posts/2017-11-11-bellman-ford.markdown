---
layout: post
title: "Day-24: Bellman-Ford Single Source Shortest Path ALgorithm"
img: rsz_24bellmanford.jpg # Add image post (optional)
date: 2017-11-11 12:54:00 +0300
description: 
tag: [Dynamic]
---
Bellman-Ford algorithm is used to calculate shortest paths from one vertex to every vertex on the graph.

However, it differs from Dijkstra in one thing: it works on negative edged graphs unlike Dijkstra.

The algorithm is rather straightforward. It iterates over all of the vertices on the graph and updates their distances.

When iterations are over, we get the shortest distances unless we have a negative weight cycle. Which would decrease the distance to negative infinity.  

Time complexity: *O(EV)* 

Here is the link of my C++ implementation of Bellman-Ford Algorithm: [Bellman-Ford Algorithm](https://github.com/abdurrezzak/100-Days-100-Algorithms-/blob/master/24.BellmanFord.cpp)
