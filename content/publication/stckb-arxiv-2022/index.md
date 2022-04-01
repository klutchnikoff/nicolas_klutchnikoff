---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Optimal 1-Wasserstein Distance for WGANs
subtitle: ''
summary: ''
authors:
- Arthur Stéphanovitch
- Ugo Tanielian
- Benoît Cadre
- admin
- Gérard Biau
tags:
- Machine learning (stat.ml)
- Machine learning (cs.lg)
- Statistics theory (math.st)
categories: []
date: '2022-01-01'
lastmod: 2022-03-31T11:33:36+02:00
featured: false
draft: false

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ''
  focal_point: ''
  preview_only: false

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: []
publishDate: '2022-03-31T09:33:36.182092Z'
publication_types:
- '0'
abstract: The mathematical forces at work behind Generative Adversarial Networks raise
  challenging theoretical issues. Motivated by the important question of characterizing
  the geometrical properties of the generated distributions, we provide a thorough
  analysis of Wasserstein GANs (WGANs) in both the finite sample and asymptotic regimes.
  We study the specific case where the latent space is univariate and derive results
  valid regardless of the dimension of the output space. We show in particular that
  for a fixed sample size, the optimal WGANs are closely linked with connected paths
  minimizing the sum of the squared Euclidean distances between the sample points.
  We also highlight the fact that WGANs are able to approach (for the 1-Wasserstein
  distance) the target distribution as the sample size tends to infinity, at a given
  convergence rate and provided the family of generative Lipschitz functions grows
  appropriately. We derive in passing new results on optimal transport theory in the
  semi-discrete setting.
publication: '*arXiv*'
doi: 10.48550/ARXIV.2201.02824
---
