---
title: Sorting Algorithms 
date: "2019-12-01T23:46:37.121Z"
template: "post"
draft: false
slug: "/posts/sorting-algorithms/"
category: "technical"
tags:
  - "sorting"
  - "algorithms"
description: "Explanation of most known Sorting Algorithms."
socialImage: ""
---

# Sorting Algorithms
Good understanding of sorting algorithms plays a very big role in the ocean of Algorithms and Problem Solving. So in this blog I am going to go through the most popular, efficient and inefficient sorting algorithms. And I will try to explain as best as I can, In the briefest words.

There are too many sorting algorithms but below is the list of mostly known sorting algorithms with their time and space complexities.

|Algorithm      | Worst                   | Average/expected                   | Best                               | Space                              |
| ------------- |:-----------------------:| ----------------------------------:| ----------------------------------:| ----------------------------------:|
|Selection sort | 0(n^2)                  | 0(n^2)                             | 0(n^2)                             | 0(n^2)                             |
|Bubble sort    | 0(n^2)                  | 0(n^2)                             | 0(n^2)                             | 0(n^2)                             |
|Insertion sort | 0(n^2)                  | 0(n^2)                             | 0(n^2)                             | 0(n^2)                             |
|Merge sort     | 0(n lg n)               | 0(n lg n)                          | 0(n lg n)                          | 0(n lg n)                          |
|Heap sort      | O(n lg n)               | ...                                | ...                                | ...                                |
|Quick sort     | 0(n^2)                  | 0(n lg n)                          | 0(n lg n)                          | 0(n lg n)                          |
|Counting sort  | 0(k+n)                  | 0(k+n)                             | 0(k+n)                             | 0(k+n)                             |
|Radix sort     | 0(d(n+k))               | 0(d(n+k))                          | 0(d(n+k))                          | 0(d(n+k))                          |
|Bucket sort    | 0(n^2)                  | 0(n)                               | 0(n)                               | 0(n)                               |
|Shell sort     | 0(n^2)                  | 0(n^2)                             | 0(n^2)                             | 0(n^2)                             |

Before we jump into these sorting algorithms individually you should know that most of sorting algorithms are classified in 2 sections/types/categories, ones which uses Decision tree paradigm and ones which do not use decision tree paradigm.  
The ones which uses the Decision Tree paradigm does comparisons in order to sort, where the non-decision tree will try other techniques, like divide and conquer.  
The Algorithms which follows Decision Tree paradigm can never beat the **O(n lg n)** time complexity but we can work on them to reduce the space complexity/requirement. The reason that they can't ever beat the **O(n lg n)** time complexity is because the decision tree has the height of **lg n**, in order to sort the list each item has to flow from the top to bottom and that is why it will always be *__n__ times __lg n__*.

 