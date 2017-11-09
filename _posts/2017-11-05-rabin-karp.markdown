---
layout: post
title: "Day-18: Rabin - Karp Algorithm"
img: rsz_18rabinkarp.jpg # Add image post (optional)
date: 2017-11-05 12:54:00 +0300
description: 
tag: [String Matching]
---

Rabin-Karp Algorithm is an efficient string matching algorithm that uses hashing to compare strings.

The algorithm searches a pattern inside of a text that is presumably longer that the pattern.

Firstly, the algorithm finds the hash value of the pattern and compares its value to every substring of the text of the same length with the pattern.

However, the hash value of the substrings are not computed in O(m) time, they are computed in O(1) time.

If a substring's hash value is the same with the pattern's, then the algorithm checks if they are indeed equal strings.

Time complexity: *O(n+m)* (If the hashing function is inefficient it can go up to O(nm))

Here is the link of my C++ implementation of Rabin-Karp: [Rabin-Karp Algorithm](https://github.com/abdurrezzak/100-Days-100-Algorithms-/blob/master/18.RabinKarp.cpp)
