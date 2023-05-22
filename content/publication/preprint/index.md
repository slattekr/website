---
abstract: "We consider the variational reconstruction framework for inverse
  problems and propose to learn a data-adaptive input-convex neural network
  (ICNN) as the regularization functional. The ICNN-based convex regularizer is
  trained adversarially to discern ground-truth images from unregularized
  reconstructions. Convexity of the regularizer is desirable since (i) one can
  establish analytical convergence guarantees for the corresponding variational
  reconstruction problem and (ii) devise efficient and provable algorithms for
  reconstruction. In particular, we show that the optimal solution to the
  variational problem converges to the ground-truth if the penalty parameter
  decays sub-linearly with respect to the norm of the noise. Further, we prove
  the existence of a sub-gradient-based algorithm that leads to a monotonically
  decreasing error in the parameter space with iterations. To demonstrate the
  performance of our approach for solving inverse problems, we consider the
  tasks of deblurring natural images and reconstructing images in computed
  tomography (CT), and show that the proposed convex regularizer is at least
  competitive with and sometimes superior to state-of-the-art data-driven
  techniques for inverse problems. "
slides: example
url_pdf: http://arxiv.org/pdf/1512.04133v1
publication_types:
  - "3"
authors:
  - Subhadip Mukherjee
  - Sören Dittmer
  - admin
  - Sebastian Lunz
  - Ozan Öktem
  - Carola-Bibiane Schönlieb
summary: We learn the regularizer from data and make sure that it is convex,
  which gives guarrantees on convergence of variational optimisation.
url_dataset: "#"
url_project: ""
publication_short: ""
url_source: "#"
url_video: "#"
publication: ""
featured: false
date: 2023-05-22T11:56:02.657Z
url_slides: ""
title: Learned convex regularizers for inverse problems
tags:
  - ""
  - convex
  - optimisation
  - Inverse problems
  - data-driven
  - regularization
  - adversarial learning
links:
  - name: Custom Link
    url: http://example.org
projects:
  - internal-project
image:
  caption: ""
  focal_point: ""
  preview_only: false
  filename: https://media.arxiv-vanity.com/render-output/5892693/figures/acr_diagram_test1.png
publishDate: 2017-01-01T00:00:00Z
url_poster: "#"
url_code: https://github.com/wowchemy/wowchemy-hugo-themes
doi: https://doi.org/10.48550/arXiv.2008.02839
---

{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}

Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/).
