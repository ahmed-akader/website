---
title: "Detection as Regression: Certified Object Detection by Median Smoothing"

authors:
- Ping-yeh Chiang
- Michael Curry
- Ahmed Abdelkader
- Aounon Kumar
- John Dickerson
- Tom Goldstein

date: 2020-11-25
doi: ""

publishDate: 2021-11-19T20:39:58.233580Z

publication_types: ["1"]

publication: In *Advances in Neural Information Processing Systems*
publication_short: In *NeurIPS*

abstract: Despite the vulnerability of object detectors to adversarial attacks, very few defenses are known to date. While adversarial training can improve the empirical robustness of image classifiers, a direct extension to object detection is very expensive. This work is motivated by recent progress on certified classification by randomized smoothing. We start by presenting a reduction from object detection to a regression problem. Then, to enable certified regression, where standard mean smoothing fails, we propose median smoothing, which is of independent interest. We obtain the first model-agnostic, training-free, and certified defense for object detection against $\ell_2$-bounded attacks.

tags:
- Deep Learning
- Adversarial Robustness

featured: false

links:
- name: Code
  url: https://github.com/Ping-C/CertifiedObjectDetection

---