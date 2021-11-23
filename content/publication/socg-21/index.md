---
title: "Approximate Nearest-Neighbor Search for Line Segments"

authors:
- Ahmed Abdelkader
- David Mount

date: 2021-02-06
doi: ""

publishDate: 2021-11-19T20:39:58.233580Z

publication_types: ["1"]

publication: In *Symposium on Computational Geometry*
publication_short: In *SoCG*

abstract: Approximate nearest-neighbor search is a fundamental algorithmic problem that continues to inspire study due its essential role in numerous contexts. In contrast to most prior work, which has focused on point sets, we consider nearest-neighbor queries against a set of line segments in $\mathbb{R}^d$, for constant dimension $d$. Given a set $S$ of $n$ disjoint line segments in $\mathbb{R}^d$ and an error parameter $\varepsilon > 0$, the objective is to build a data structure such that for any query point $q$, it is possible to return a line segment whose Euclidean distance from $q$ is at most $(1+\varepsilon)$ times the distance from $q$ to its nearest line segment. We present a data structure for this problem with storage $O((n^2/\varepsilon^d) \log (\Delta/\varepsilon))$ and query time $O(\log(\max(n,\Delta)/\varepsilon))$, where $\Delta$ is the spread of the set of segments $S$. Our approach is based on a covering of space by anisotropic elements, which align themselves according to the orientations of nearby segments.

tags:
- Computational Geometry
- Anisotropy
- Approximation Algorithms

featured: true

links:
- name: LIPIcs
  url: https://drops.dagstuhl.de/opus/volltexte/2021/13803/
- name: arXiv
  url: https://arxiv.org/abs/2103.16071
- name: Slides
  url: https://www.dropbox.com/s/owmep4gvjngeeth/SoCG21_talk.pdf
- name: Video
  url: https://drive.google.com/file/d/1fNWVBZQ1jNMYm_XYNX2mn3Pb-ctO_cg-
- name: Video-2
  url: https://drive.google.com/file/d/1ElNOPe9PuvonDuN994nRkUQtzeHs_v5T

---