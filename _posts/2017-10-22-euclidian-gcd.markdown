---
layout: post
title: "Day-4: Euclidian GCD Algorithm"
img: rsz_4euclidiangcd.jpg # Add image post (optional)
date: 2017-10-22 12:54:00 +0300
description: You’ll find this post in your `_posts` directory. Go ahead and edit it and re-build the site to see your changes. # Add post description (optional)
tag: [Sorting]
---

Euclidian GCD algorithm is used for calculating greatest common divisor of two numbers- depending on data type, the numbers may be double or int etc. 

The algorithm has two steps:
  -> Checks if b divides a
    ->If yes, returns b immediately
    ->If not, tries the same for b and a%b
    
Time complexity: *O(log(ab))* (It happens when a and b are Fibonacci numbers that are consecutive)

Here is the link of my C++ implementation of Euclidian GCD: [Euclidian GCD](https://github.com/abdurrezzak/100-Days-100-Algorithms-/blob/master/4.EuclidianGCD.cpp)
