---
title: "VoroCrust: Voronoi meshing without clipping"
date: 2020-05-08
publishDate: 2021-11-19T20:39:58.265869Z
authors: ["Ahmed Abdelkader", "Chandrajit Bajaj", "Mohamed Ebeida", "Ahmed Mahmoud", "Scott Mitchell", "John Owens", "Ahmad Rushdi"]
publication_types: ["2"]
abstract: "Polyhedral meshes are increasingly becoming an attractive option with particular advantages over traditional meshes for certain applications. What has been missing is a robust polyhedral meshing algorithm that can handle broad classes of domains exhibiting arbitrarily curved boundaries and sharp features. In addition, the power of primal-dual mesh pairs, exemplified by Voronoi-Delaunay meshes, has been recognized as an important ingredient in numerous formulations. The VoroCrust algorithm is the first provably correct algorithm for conforming polyhedral Voronoi meshing for non-convex and non-manifold domains with guarantees on the quality of both surface and volume elements. A robust refinement process estimates a suitable sizing field that enables the careful placement of Voronoi seeds across the surface, circumventing the need for clipping and avoiding its many drawbacks. The algorithm has the flexibility of filling the interior by either structured or random samples while preserving all sharp features in the output mesh. We demonstrate the capabilities of the algorithm on a variety of models and compare against state-of-the-art polyhedral meshing methods based on clipped Voronoi cells establishing the clear advantage of VoroCrust output."
featured: false
publication: "*ACM Transactions on Graphics (TOG) & SIGGRAPH*"
---

