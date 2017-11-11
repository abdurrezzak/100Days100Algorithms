---
layout: post
title: "Day-21: Prim's Minimum Spanning Tree Algorithm"
img: rsz_21primalgorithm.png # Add image post (optional)
date: 2017-11-08 12:54:00 +0300
description: 
tag: [Greedy]
---

Prim's MST algorithm is a good example of how powerful Greedy problem solving paradigm can be. 

The algorithm assigns key values to every node and chooses one to start with.

In every iteration, the algorithm adds a new edge to the existing MST(firstly just one vertex).

The edge is of the smallest length.

Finally, we get an MST.

Time complexity: *O(ElogV)* However, in my implementation, as I did not use a priority queue, complexity becomes O(V^2) 

Here is the link of my C++ implementation of Prim's Algorithm: [Prim's Algorithm](https://github.com/abdurrezzak/100-Days-100-Algorithms-/blob/master/21.PrimAlgorithm.cpp)
