---
layout: post
title: "Day-26: Minimum Subset Difference Partition"
img: rsz_26minimumpartition.jpg # Add image post (optional)
date: 2017-11-13 12:54:00 +0300
description: 
tag: [Dynamic]
---

This algorithm is a very basic Dynamic Programming algorithm.

It takes an array find the minimum difference of subset sums achievable by partitioning the array.

When iterating through the array, the algorithm decides whether to include the current element or not. 

To do that, it makes a recursive call.

Via memoizing, it becomes very fast.

Time complexity: *O(n*sum)* which depends on the sum of the alements of the array.

Here is the link of my C++ implementation of Minimum Partition : [Minimum Partition](https://github.com/abdurrezzak/100-Days-100-Algorithms-/blob/master/26.MinimumPartition.cpp)
