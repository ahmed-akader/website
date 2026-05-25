---
title: "Differentiable Approximations for Distance Queries"

authors:
- Ahmed Abdelkader
- David Mount

date: 2025-01-12
doi: ""

publishDate: 2025-01-12T20:39:58.233580Z

publication_types: ["1"]

publication: "In *ACM-SIAM Symposium on Discrete Algorithms*"
publication_short: "In *SODA*"

abstract: |
    The widespread use of gradient-based optimization has motivated the adaptation of various classical algorithms into differentiable solvers compatible with learning pipelines. In this paper, we investigate the enhancement of traditional geometric query problems such that the result consists of both the geometric function as well as its gradient. Specifically, we study the fundamental problem of distance queries against a set of points P in ℝd, which also underlies various similarity measures for learning algorithms.

    The main result of this paper is a multiplicative (1 + epsilon)-approximation of the Euclidean distance to P which is differentiable at all points in R^d \ P with asymptotically optimal bounds on the norms of its gradient and Hessian, from a data structure with storage and query time matching state-of-the-art results for approximate nearest-neighbor searching. The approximation is realized as a regularized distance through a partition-of-unity framework, which efficiently blends multiple local approximations, over a suitably defined covering of space, into a smooth global approximation. In order to obtain the local distance approximations in a manner that facilitates blending, we develop a new approximate Voronoi diagram based on a simple point-location data structure, simplifying away both the lifting transformation and ray shooting.

tags:
- Selected
- Computational Geometry
- Approximation Algorithms

projects:
- algos

featured: false

links:
- name: SIAM
  url: https://epubs.siam.org/doi/abs/10.1137/1.9781611978322.172

---
