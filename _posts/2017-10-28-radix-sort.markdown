---
layout: post
title: "Day-10: Radix Sort"
img: rsz_10radixsort.jpg # Add image post (optional)
date: 2017-10-28 12:54:00 +0300
description: 
tag: [Sorting]
---

Radix sort is another placing based sorting algorithm that has expected linear time.

Radix sort basically takes an array and using Counting Sort as a subroutine sorts all of the digits.

At the end we get a sorted array.

Time complexity: *O(d(n+b))* where d is the number of digits of the greates element. 
Note that complexity becomes *O(n)* when we onsider base ten numbers.

Here is the link of my C++ implementation of Radix Sort: [Radix Sort](https://github.com/abdurrezzak/100-Days-100-Algorithms-/blob/master/10.RadixSort.cpp)
