---
title: "Smooth Distance Approximation"

authors:
- Ahmed Abdelkader
- David Mount

date: 2023-08-30
doi: ""

publishDate: 2023-08-30T00:00:00.000000Z

publication_types: ["1"]

publication: In *European Symposium on Algorithms*
publication_short: In *ESA*

abstract: |
    Traditional problems in computational geometry involve aspects that are both discrete and continuous. One such example is nearest-neighbor searching, where the input is discrete, but the result depends on distances, which vary continuously. In many real-world applications of geometric data structures, it is assumed that query results are continuous, free of jump discontinuities. This is at odds with many modern data structures in computational geometry, which employ approximations to achieve efficiency, but these approximations often suffer from discontinuities.
    
    In this paper, we present a general method for transforming an approximate but discontinuous data structure into one that produces a smooth approximation, while matching the asymptotic space efficiencies of the original. We achieve this by adapting an approach called the partition-of-unity method, which smoothly blends multiple local approximations into a single smooth global approximation.
    
    We illustrate the use of this technique in a specific application of approximating the distance to the boundary of a convex polytope in ℝ^d from any point in its interior. We begin by developing a novel data structure that efficiently computes an absolute ε-approximation to this query in time O(log (1/ε)) using O(1/ε^{d/2}) storage space. Then, we proceed to apply the proposed partition-of-unity blending to guarantee the smoothness of the approximate distance field, establishing optimal asymptotic bounds on the norms of its gradient and Hessian.

tags:
- Selected
- Computational Geometry
- Approximation Algorithms

projects:
- algos

featured: false

links:
- name: LIPIcs
  url: https://drops.dagstuhl.de/opus/volltexte/2023/18658/
- name: PDF
  url: https://drops.dagstuhl.de/opus/volltexte/2023/18658/pdf/LIPIcs-ESA-2023-5.pdf
- name: Slides
  url: https://www.dropbox.com/scl/fi/ecczahah3eviaudsafk19/ESA23_talk.pdf

---
