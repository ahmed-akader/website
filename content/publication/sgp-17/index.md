---
title: "A Constrained Resampling Strategy for Mesh Improvement"

authors:
- Ahmed Abdelkader
- Ahmed Mahmoud
- Ahmad Rushdi
- Scott Mitchell
- John Owens
- Mohamed Ebeida

date: 2017-08-14
doi: ""

publishDate: 2021-11-19T20:39:58.233580Z

publication_types: ["2"]

publication: In *Computer Graphics Forum - Proceedings of the Eurographics Symposium on Geometry Processing*
publication_short: In *CGF/SGP*

abstract: In many geometry processing applications, it is required to improve an initial mesh in terms of multiple quality objectives. Despite the availability of several mesh generation algorithms with provable guarantees, such generated meshes may only satisfy a subset of the objectives. The conflicting nature of such objectives makes it challenging to establish similar guarantees for each combination, e.g., angle bounds and vertex count. In this paper, we describe a versatile strategy for mesh improvement by interpreting quality objectives as spatial constraints on resampling and develop a toolbox of local operators to improve the mesh while preserving desirable properties. Our strategy judiciously combines smoothing and transformation techniques allowing increased flexibility to practically achieve multiple objectives simultaneously. We apply our strategy to both planar and surface meshes demonstrating how to simplify Delaunay meshes while preserving element quality, eliminate all obtuse angles in a complex mesh, and maximize the shortest edge length in a Voronoi tessellation far better than the state-of-the-art.

tags: ["Computational Geometry", "Shape Modeling"]

featured: false

links:
- name: Code
  url: https://github.com/Ahdhn/MeshImp

---
