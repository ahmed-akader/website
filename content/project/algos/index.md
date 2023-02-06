---
title: Approximation Algorithms
summary: Efficient evaluation of distance and membership queries in high-dimensional spaces
tags:
- Computational Geometry
- Anisotropy
- Approximation Algorithms
date: "2010-04-27T00:00:00Z"

profile: false

---

Geometric spaces naturally provide convenient representations for a variety of data types besides, of course, the 3D objects we encounter in the real world. The notion of proximity plays an important roles in many computational problems defiend on such geometric data, whenever the distance or similarity between entities is part of the formulation. Due to the fundamental limitations on our practical computational resources, we have to resort to approximations when evaluating some of the basic geometric questions involved when dealing with high-dimensional data.

My research in approximation algorithms revolves around the efficient covering of space using anisotropic elements, enabling fast look-ups while using the minimal amount of storage necessary. My first result in this area presented an optimal and greatly simplified data structure for approximate polytope membership testing. The data structure can be intuitively understood as a standard hierarcy of Delone sets with respect to the intrinsic Hilbert metric defined on the interior of the polytope. Through the close relationship between convex polytopes and approximate nearest-neighbor searching, I continued to apply this methodology to develop data structures for nearest-neighbor searching with non-Euclidean distance functions, e.g., convex distance functions and Bregman divergences, as well as highly anisotropic non-point sites, i.e., line segments.

My approach to geometric approximation algorithms is heavily inspired by my background in mesh generation. In my ongoing research, I continue to develop my understanding of distance functions with a particular focus on their differential properties, i.e., anisotropy. Some of the questions I ponder along this direction are directly relevant to the efficient representation and reconstruction of 3D surfaces.
