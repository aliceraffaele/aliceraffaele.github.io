---
title: 'Listing bonds on Discrete Applied Mathematics'
date: 2024-01-26
permalink: /posts/2024/01/dam-listing-bonds/
tags:
  - enumeration
  - listing algorithms
  - bonds
  - publications
---

Finally, the first paper extracted from my Ph.D. thesis have been published in Discrete Applied Mathematics and is available [online](https://doi.org/10.1016/j.dam.2024.01.004).

Romeo Rizzi, Takeaki Uno, and I worked on some fundamental concepts of graph theory: connectivity and cuts. Given an undirected and connected graph, a cut is a set of edges that, if removed, would disconnect the graph. A cut can also be represented as a bipartition of the graph’s vertices. Usually, in linear programming, we typically look for a *minimum* cut, i.e., a cut with the minimum number of edges or the smallest capacity. To compute one, all possible bipartitions of vertices can be examined by checking the corresponding set of edges connecting the two partitions. However, this approach is inefficient, given the exponential number of bipartitions. Rather than doing this, one could apply the famous max flow-min cut theorem by Ford and Fulkerson and rely on polynomial-time algorithms for the maximum-flow problem. What if we want to obtain, instead, all the cuts? To represent them, we can compute only those that are *minimal* under inclusion. When a cut is minimal, none of its subsets is also a cut, and the corresponding bipartition of vertices leads to two connected induced subgraphs.

The problem of listing all minimal cuts, or *bonds*, of a graph has been quite studied in enumeration. The state of the art corresponds to the polynomial-delay algorithm by Tsukiyama et al. (1980), which allows outputting a new bond in a time linear in the number of edges of the given graph. In this paper, we propose two new algorithms, the former having the same time complexity as the one by Tsukiyama et al. (1980), whereas the latter improves this by relying on dynamic-graph algorithms. In this way, it is possible to obtain the first polylogarithmic-delay listing algorithm for bonds, linear in the number of vertices of the given graph.
