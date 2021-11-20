---
title: "Sampling Conditions for Conforming Voronoi Meshing by the VoroCrust Algorithm"

authors:
- Ahmed Abdelkader
- Chandrajit Bajaj
- Mohamed Ebeida
- Ahmed Mahmoud
- Scott Mitchell
- John Owens
- Ahmad Rushdi

date: 2018-06-08
doi: ""

publishDate: 2021-11-19T20:39:58.233580Z

publication_types: ["1"]

publication: In *Symposium on Computational Geometry*
publication_short: In *SoCG*

abstract: We study the problem of decomposing a volume bounded by a smooth surface into a collection of Voronoi cells. Unlike the dual problem of conforming Delaunay meshing, a principled solution to this problem for generic smooth surfaces remained elusive. VoroCrust leverages ideas from alpha-shapes and the power crust algorithm to produce unweighted Voronoi cells conforming to the surface, yielding the first provably-correct algorithm for this problem. Given an epsilon-sample on the bounding surface, with a weak sigma-sparsity condition, we work with the balls of radius delta times the local feature size centered at each sample. The corners of this union of balls are the Voronoi sites, on both sides of the surface. The facets common to cells on opposite sides reconstruct the surface. For appropriate values of epsilon, sigma and delta, we prove that the surface reconstruction is isotopic to the bounding surface. With the surface protected, the enclosed volume can be further decomposed into an isotopic volume mesh of fat Voronoi cells by generating a bounded number of sites in its interior. Compared to state-of-the-art methods based on clipping, VoroCrust cells are full Voronoi cells, with convexity and fatness guarantees. Compared to the power crust algorithm, VoroCrust cells are not filtered, are unweighted, and offer greater flexibility in meshing the enclosed volume by either structured grids or random samples.

tags: ["Computational Geometry", "Shape Modeling", "Voronoi Meshing"]

featured: false

links:
- name: Video
  url: https://www.youtube.com/watch?v=PqvTZnekZlY

---
