---
title: "Mull-Tokens: Modality-Agnostic Latent Thinking"

authors:
- Arijit Ray
- Ahmed Abdelkader
- Chengzhi Mao
- Bryan A. Plummer
- Kate Saenko
- Ranjay Krishna
- Leonidas Guibas
- Wen-Sheng Chu

date: 2026-06-07
doi: ""

publishDate: 2026-04-11T20:39:58.233580Z

publication_types: ["1"]

publication: "In *IEEE/CVF Conference on Computer Vision and Pattern Recognition (Findings)*"
publication_short: "In *CVPR Findings*"

abstract: |
  Reasoning goes beyond language; the real world requires reasoning about space, time, affordances, and much more that words alone cannot convey. Existing multimodal models exploring the potential of reasoning with images are brittle and do not scale. They rely on calling specialist tools, costly generation of images, or handcrafted reasoning data to switch between text and image thoughts. Instead, we offer a simpler alternative -- Mull-Tokens -- modality-agnostic latent tokens pre-trained to hold intermediate information in either image or text modalities to let the model think free-form towards the correct answer. We investigate best practices to train Mull-Tokens inspired by latent reasoning frameworks. We first train Mull-Tokens using supervision from interleaved text-image traces, and then fine-tune without any supervision by only using the final answers. Across four challenging spatial reasoning benchmarks involving tasks such as solving puzzles and taking different perspectives, we demonstrate that Mull-Tokens improve upon several baselines utilizing text-only reasoning or interleaved image-text reasoning, achieving a +3% average improvement and up to +16% on a puzzle solving reasoning-heavy split compared to our strongest baseline. Adding to conversations around challenges in grounding textual and visual reasoning, Mull-Tokens offers a simple solution to abstractly think in multiple modalities.

tags:
- Selected
- Reasoning
- Computer Vision

projects:
- cv

featured: true

links:
- name: arXiv
  url: https://arxiv.org/abs/2512.10941

---
