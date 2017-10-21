---
layout: post
title: "Day-1: Binary Search"
img: binarysearch.png # Add image post (optional)
date: 2017-10-19 12:54:00 +0300
description: You’ll find this post in your `_posts` directory. Go ahead and edit it and re-build the site to see your changes. # Add post description (optional)
tag: [Travel]
---

Binary Search algorithm is a divide and conquer algorithm that performs efficient search on sorted arrays. 

The algorithms first looks for the middle element and compares it with the element we are searching. If the middle element is the same with the desired element, algorithm returns. Otherwise, there emerges two probabilities. Eithe middle element is bigger than the element we are searching or it is smaller. 

If the first probability is the case, we make a recursive call to left part of the array. Otherwise, we make a recursive call on the right side of the array.

At the end, if the algorithm does not encounter the element in the array, it returns -1.

Here is the link of my C++ implementation of binary search: [Binary Search](https://github.com/abdurrezzak/100-Days-100-Algorithms-/blob/master/1.BinarySearch.cpp)

