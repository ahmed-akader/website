---
title: "Approximate Nearest Neighbor Searching with Non-Euclidean and Weighted Distances"
date: 2018-01-11
publishDate: 2021-11-19T20:39:58.259951Z
authors: ["Ahmed Abdelkader", "Sunil Arya", "Guilherme da Fonseca", "David M. Mount"]
publication_types: ["1"]
abstract: "We present a new approach to ε-approximate nearest-neighbor queries in fixed dimension under a variety of non-Euclidean distances. We consider two families of distance functions: (a) convex scaling distance functions including the Mahalanobis distance, the Minkowski metric and multiplicative weights, and (b) Bregman divergences including the Kullback-Leibler divergence and the Itakura-Saito distance.

As the fastest known data structures rely on the lifting transformation, their application is limited to the Euclidean metric, and alternative approaches for other distance functions are much less efficient. We circumvent the reliance on the lifting transformation by a careful application of convexification, which appears to be relatively new to computational geometry.

We are given n points in ℝ^d, each a site possibly defining its own distance function. Under mild assumptions on the growth rates of these functions, the proposed data structures answer queries in logarithmic time using O(n log(1/ε)/ε^d/2) space, which nearly matches the best known results for the Euclidean metric."
featured: false
publication: "*ACM-SIAM Symposium on Discrete Algorithms (SODA)*"
---

