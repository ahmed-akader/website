---
title: "Approximate Nearest-Neighbor Search for Line Segments"
date: 2021-02-06
publishDate: 2021-11-19T20:39:58.262654Z
authors: ["Ahmed Abdelkader", "David M. Mount"]
publication_types: ["1"]
abstract: "Approximate nearest-neighbor search is a fundamental algorithmic problem that continues to inspire study due its essential role in numerous contexts. In contrast to most prior work, which has focused on point sets, we consider nearest-neighbor queries against a set of line segments in ℝ^d, for constant dimension d. Given a set S of n disjoint line segments in ℝ^d and an error parameter ε > 0, the objective is to build a data structure such that for any query point q, it is possible to return a line segment whose Euclidean distance from q is at most (1+ε) times the distance from q to its nearest line segment. We present a data structure for this problem with storage O((n²/ε^d) log (Δ/ε)) and query time O(log (max(n,Δ)/ε)), where Δ is the spread of the set of segments S. Our approach is based on a covering of space by anisotropic elements, which align themselves according to the orientations of nearby segments."
featured: false
publication: "*Symposium on Computational Geometry (SoCG)*"
---
