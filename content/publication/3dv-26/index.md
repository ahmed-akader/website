---
title: "Marginalized Bundle Adjustment: Multi-View Camera Pose from Monocular Depth Estimates"

authors:
- Shengjie Zhu
- Ahmed Abdelkader
- Mark J. Matthews
- Xiaoming Liu
- Wen-Sheng Chu

date: 2026-04-20
doi: ""

publishDate: 2026-04-20T20:39:58.233580Z

publication_types: ["1"]

publication: "In *International Conference on 3D Vision*"
publication_short: "In *3DV*"

abstract: |
  Structure-from-Motion (SfM) is a fundamental 3D vision task for recovering camera parameters and scene geometry from multi-view images. While recent deep learning advances enable accurate Monocular Depth Estimation (MDE) from single images without depending on camera motion, integrating MDE into SfM remains a challenge. Unlike conventional triangulated sparse point clouds, MDE produces dense depth maps with significantly higher error variance. Inspired by modern RANSAC estimators, we propose Marginalized Bundle Adjustment (MBA) to mitigate MDE error variance leveraging its density. With MBA, we show that MDE depth maps are sufficiently accurate to yield SoTA or competitive results in SfM and camera relocalization tasks. Through extensive evaluations, we demonstrate consistently robust performance across varying scales, ranging from few-frame setups to large multi-view systems with thousands of images. Our method highlights the significant potential of MDE in multi-view 3D vision.

tags:
- Selected
- 3D Vision
- Computer Vision

projects:
- cv

featured: false

links:
- name: Webpage
  url: https://marginalized-ba.github.io/
- name: OpenReview
  url: https://openreview.net/forum?id=OMTumHheAo
- name: arXiv
  url: https://arxiv.org/abs/2602.18906
- name: Code
  url: https://github.com/ShngJZ/Marginalized-Bundle-Adjustment

---
