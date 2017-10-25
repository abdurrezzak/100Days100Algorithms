---
layout: post
title: "Day-7: Quicksort"
img: rsz_7quicksort.png # Add image post (optional)
date: 2017-10-25 12:54:00 +0300
description: You’ll find this post in your `_posts` directory. Go ahead and edit it and re-build the site to see your changes. # Add post description (optional)
tag: [Sorting]
---

Quicksort is one of the most efficient and famous sorting algorithms.

Quicksort is an inplace divide and conquer algorithm. The key feature of the quicksort is the partition that takes O(n) time.

There are couple of different partition methods available. In the implementation provided with the link below is Lomuto's partition. 

Partition, simply divides the array into two parts one of them consists of the elements that are smaller than the chosen pivot, the other part has the bigger ones.

The pivot is the last element of the array in case of Lomuto's partition.

The algorithm partitions the array and makes recursive calls to both sides to apply the same. 

At the end, the array is sorted.

Time complexity: *O(nlogn)*

Here is the link of my C++ implementation of Quicksort: [Quicksort](https://github.com/abdurrezzak/100-Days-100-Algorithms-/blob/master/7.QuickSort.cpp)
