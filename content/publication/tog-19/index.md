---
title: "VoroCrust: Voronoi meshing without clipping"

authors:
- Ahmed Abdelkader
- Chandrajit Bajaj
- Mohamed Ebeida
- Ahmed Mahmoud
- Scott Mitchell
- John Owens
- Ahmad Rushdi

date: 2020-05-08
doi: ""

publishDate: 2021-11-19T20:39:58.233580Z

publication_types: ["2"]

publication: In *ACM Transactions on Graphics (TOG)*
publication_short: In *TOG/SIGGRAPH*

abstract: Polyhedral meshes are increasingly becoming an attractive option with particular advantages over traditional meshes for certain applications. What has been missing is a robust polyhedral meshing algorithm that can handle broad classes of domains exhibiting arbitrarily curved boundaries and sharp features. In addition, the power of primal-dual mesh pairs, exemplified by Voronoi-Delaunay meshes, has been recognized as an important ingredient in numerous formulations. The VoroCrust algorithm is the first provably correct algorithm for conforming polyhedral Voronoi meshing for non-convex and non-manifold domains with guarantees on the quality of both surface and volume elements. A robust refinement process estimates a suitable sizing field that enables the careful placement of Voronoi seeds across the surface, circumventing the need for clipping and avoiding its many drawbacks. The algorithm has the flexibility of filling the interior by either structured or random samples while preserving all sharp features in the output mesh. We demonstrate the capabilities of the algorithm on a variety of models and compare against state-of-the-art polyhedral meshing methods based on clipped Voronoi cells establishing the clear advantage of VoroCrust output.

tags:
- Computational Geometry
- Shape Modeling
- Voronoi Meshing

featured: true

url_video: https://www.youtube.com/watch?v=PqvTZnekZlY

links:
- name: ACM DL
  url: https://dl.acm.org/doi/abs/10.1145/3337680
- name: arXiv:
  url: https://arxiv.org/abs/1902.08767
- name: Media
  url: https://www.sandia.gov/labnews/2020/04/23/vorocrust/

---
