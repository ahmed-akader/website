---
title: "Mining Attribute Subspaces for Efficient Fine-tuning of 3D Foundation Models"

authors:
- Yu Jiang
- Hanwen Jiang
- Ahmed Abdelkader
- Wen-Sheng Chu
- Brandon Y. Feng
- Zhangyang Wang
- Qixing Huang

date: 2026-06-07
doi: ""

publishDate: 2026-04-11T20:39:58.233580Z

publication_types: ["1"]

publication: In *IEEE/CVF Conference on Computer Vision and Pattern Recognition*
publication_short: In *CVPR*

abstract: With the emergence of 3D foundation models, there is growing interest in fine-tuning them for downstream tasks, where LoRA is the dominant fine-tuning paradigm. As 3D datasets exhibit distinct variations in texture, geometry, camera motion, and lighting, there are interesting fundamental questions: 1) Are there LoRA subspaces associated with each type of variation? 2) Are these subspaces disentangled (i.e., orthogonal to each other)? 3) How do we compute them effectively? This paper provides answers to all these questions. We introduce a robust approach that generates synthetic datasets with controlled variations, fine-tunes a LoRA adapter on each dataset, and extracts a LoRA sub-space associated with each type of variation. We show that these subspaces are approximately disentangled. Integrating them leads to a reduced LoRA subspace that enables efficient LoRA fine-tuning with improved prediction accuracy for downstream tasks. In particular, we show that such a reduced LoRA subspace, despite being derived entirely from synthetic data, generalizes to real datasets. An ablation study validates the effectiveness of the choices in our approach. 

tags:
- Selected
- 3D Vision
- Computer Vision

projects:
- cv

featured: false

links:
- name: arXiv
  url: https://arxiv.org/abs/2604.10095

---
