---
layout: post
title: "Day-22: Kruskal's Minimum Spanning Tree Algorithm"
img: rsz_22kruskalalgorithm.png # Add image post (optional)
date: 2017-11-09 12:54:00 +0300
description: 
tag: [Greedy]
---

Kruskal's algorithm is another well known greedy MST algorithm. 

The main difference between Prim's and Kruskal's algorithms is that Kruskal's algorithm constructs multiple small MST's to reach one MST; meanwhile, Prim's algorithm constructs just one MST from one vertex.

The algorithm firstly creates individual sets for every vertex.

Sorts the edges regarding their weights.

Starting from the lightest, creates small MST's using those vertices and edges.

Time complexity: *O(V+ ElogV)* 

Here is the link of my C++ implementation of Kruskal's Algorithm: [Kruskal's Algorithm](https://github.com/abdurrezzak/100-Days-100-Algorithms-/blob/master/22.KruskalAlgorithm.cpp)
