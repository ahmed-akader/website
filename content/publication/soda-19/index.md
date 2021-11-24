---
title: "Approximate Nearest Neighbor Searching with Non-Euclidean and Weighted Distances"

authors:
- Ahmed Abdelkader
- Sunil Arya
- Guilherme da Fonseca
- David Mount

date: 2019-01-06
doi: ""

publishDate: 2021-11-19T20:39:58.233580Z

publication_types: ["1"]

publication: In *ACM-SIAM Symposium on Discrete Algorithms*
publication_short: In *SODA*

abstract: |
    We present a new approach to $\varepsilon$-approximate nearest-neighbor queries in fixed dimension under a variety of non-Euclidean distances. We consider two families of distance functions: (a) convex scaling distance functions including the Mahalanobis distance, the Minkowski metric and multiplicative weights, and (b) Bregman divergences including the Kullback-Leibler divergence and the Itakura-Saito distance.
    
    As the fastest known data structures rely on the lifting transformation, their application is limited to the Euclidean metric, and alternative approaches for other distance functions are much less efficient. We circumvent the reliance on the lifting transformation by a careful application of convexification, which appears to be relatively new to computational geometry.
    
    We are given $n$ points in $\mathbb{R}^d$, each a site possibly defining its own distance function. Under mild assumptions on the growth rates of these functions, the proposed data structures answer queries in logarithmic time using $O(n \log(1/\varepsilon)/\varepsilon^{d/2})$ space, which nearly matches the best known results for the Euclidean metric.

tags:
- Computational Geometry
- Approximation Algorithms

projects:
- algos

featured: false

links:
- name: SIAM
  url: https://epubs.siam.org/doi/abs/10.1137/1.9781611975482.23
- name: PDF
  url: https://www.dropbox.com/s/lay4oew9bjvew6t/SODA19_convexification.pdf
- name: Slides
  url: https://www.dropbox.com/s/vy1a4zl8f651a3u/SODA19_ANN_talk.pdf

---
