---
layout: post
title: "Day-19: Knuth-Morris-Pratt Algorithm(KMP)"
img: rsz_19kmp.jpg # Add image post (optional)
date: 2017-11-06 12:54:00 +0300
description: 
tag: [String Matching]
---

KMP is a very famous string searching algorithm. 

The algorithm, takes a text and a pattern to search in the text. 

What makes KMP special is that it computes a failure function which basically tells the program where to move next.

Preprocessing takes O(m) time where m is the length of the pattern.

Time complexity: *O(n+m)* (May take up to O(mn) when the pattern is so "inconvenient". e.g "xaaaaaaaaaaaaaa")

Here is the link of my C++ implementation of KMP: [Knuth-Morris-Pratt Algorithm](https://github.com/abdurrezzak/100-Days-100-Algorithms-/blob/master/19.KMP.cpp)
