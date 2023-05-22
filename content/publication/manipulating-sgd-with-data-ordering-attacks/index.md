---
title: Manipulating SGD with data ordering attacks
publication_types:
  - "1"
authors:
  - Ilia Shumailov
  - admin
  - Dmitry Kazhdan
  - Yiren Zhao
  - Nicolas Papernot
  - Murat A Erdogdu
  - Ross J Anderson
doi: https://doi.org/10.48550/arXiv.2104.09667
publication: NeurIPS 2021
abstract: "Machine learning is vulnerable to a wide variety of attacks. It is
  now well understood that by changing the underlying data distribution, an
  adversary can poison the model trained with it or introduce backdoors. In this
  paper we present a novel class of training-time attacks that require no
  changes to the underlying dataset or model architecture, but instead only
  change the order in which data are supplied to the model. In particular, we
  find that the attacker can either prevent the model from learning, or poison
  it to learn behaviours specified by the attacker. Furthermore, we find that
  even a single adversarially-ordered epoch can be enough to slow down model
  learning, or even to reset all of the learning progress. Indeed, the attacks
  presented here are not specific to the model or dataset, but rather target the
  stochastic nature of modern learning procedures. We extensively evaluate our
  attacks on computer vision and natural language benchmarks to find that the
  adversary can disrupt model training and even introduce backdoors. "
draft: false
featured: false
image:
  filename: https://d3i71xaburhd42.cloudfront.net/2970f2c2c928ba8f8ce55ddd312b463869e75c84/3-Figure1-1.png
  focal_point: Smart
  preview_only: false
date: 2021-05-01T12:06:30.051Z
---
