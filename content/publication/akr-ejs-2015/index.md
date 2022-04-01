---
# Documentation: https://wowchemy.com/docs/managing-content/

title: On clustering procedures and nonparametric mixture estimation
subtitle: ''
summary: ''
authors:
- Stéphane Auray
- admin
- Laurent Rouvière
tags:
- 62g07
- 62h30
categories: []
date: '2015-01-01'
lastmod: 2022-03-31T11:33:38+02:00
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
publishDate: '2022-03-31T09:33:38.139749Z'
publication_types:
- '2'
abstract: This paper deals with nonparametric estimation of conditional den-sities
  in mixture models in the case when additional covariates are available. The proposed
  approach consists of performing a prelim-inary clustering algorithm on the additional
  covariates to guess the mixture component of each observation. Conditional densities
  of the mixture model are then estimated using kernel density estimates ap-plied
  separately to each cluster. We investigate the expected L 1 -error of the resulting
  estimates and derive optimal rates of convergence over classical nonparametric density
  classes provided the clustering method is accurate. Performances of clustering algorithms
  are measured by the maximal misclassification error. We obtain upper bounds of this
  quantity for a single linkage hierarchical clustering algorithm. Lastly, applications
  of the proposed method to mixture models involving elec-tricity distribution data
  and simulated data are presented.
publication: '*Electronic Journal of Statistics*'
doi: 10.1214/15-EJS995
---
