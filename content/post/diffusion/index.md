---
title: Denoising Diffusion and Graphical Models
subtitle: A case study discussing variational inference and its connections to score approximation.
summary: A case study discussing variational inference and its connections to score approximation. 

# Link this post with a project
projects: []

# Date published
date: '2024-02-02T00:00:00Z'

# Date updated
lastmod: '2024-02-02T00:00:00Z'

# Is this an unpublished draft?
draft: true

# Show this page in the Featured widget?
featured: false

# Featured image
# Place an image named `featured.jpg/png` in this page's folder and customize its options here.
image:
  caption: 'Image credit: HotPot.ai'
  focal_point: ''
  placement: 2
  preview_only: false

authors:
  - admin
  - Alvaro Ribot

---

## Main Idea

Graphical models allow us to describe distributions implicitly via their conditional indepen-
dence structure. They are especially useful for high-dimensional distributions. However, sampling
from them poses many algorithmic challenges.

Using a variational inference perspective, one can try to approximate such distributions with
generative models, from which one would be able to obtain approximate samples. Here, we give
a thorough description of how to tackle this problem with diffusion-based generative models.
In particular, we address an interesting connection between variational inference in graphical
models and score approximation in diffusion models.

In conclusion, the aim of this report is to exhibit how to leverage Diffusion models to sample
efficiently from high-dimensional graphical models. Based on the main results from literature, we focus
on how to apply Denoising Diffusion Probabilistic Models (DDPMs) for Ising models.
