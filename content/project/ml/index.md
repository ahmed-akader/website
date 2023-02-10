---
title: Machine Learning
summary: Mitigating the vulnerabilities of modern machine learning workflows
tags:
- Deep Learning
- Adversarial Robustness
- Data Analysis
date: "2013-04-27T00:00:00Z"

profile: false

---

Despite the unprecedented performance gains brought about by deep neural networks for computer vision and other tasks, they exhibit critical vulnerabilities under carefully crafted perturbations applied adversarially to input images. Intuitively, a neural network encodes a mapping of inputs to outputs, where perturbing the inputs in *semantically-inessential* ways can trick the network to produce a *semantically-incorrect* output. Given the increasingly-important role neural networks play in very sensitive applications, the study of adversarial attacks and defenses has become one of the main areas of machine learning research. Due to the complexity and lack of full theoretical characterization of deep neural networks, the study of adversarial robustness touches upon the fundamental operations of neural network training and inference, as well as parameter initialization and dataset curation.

A primary theoretical problem in adversarial robustness is to endow the machine learning model to compute an auxiliary output as a certificate summarizing the degree of confidence in the computed outputs. My research work introduced some of the first approaches to the certification of image classification models under *patch attacks*, which are closely related to physical attacks that can be realized in the real world, as well as the certification of object detection models, which feature prominently in the majority of computer vision systems. My research work also questioned some of the standard machine learning development workflows, i.e., transfer learning, where a costly pretrained model is used to boost the training of new models, demonstrating how simple vulnerabilities in the pretrained model are readily inherited by the new models. To further understand the role of the dataset in the difficulty of learning and defending against adversarial attacks, my research work provided some of the first estimates of the intrinsic dimension of popular image datasets; an important statistical quantity that is often cited for intuitive explanations of the success of deep learning in practice.

Beyond the questions I studied in my past research, I continue to be intrigued by the potential to apply powerful neural models to classical problems in visual perception. I am specifically interested in biologically-inspired networks and implicit neural representations.
