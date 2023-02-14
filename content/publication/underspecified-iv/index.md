---
abstract: 
  Instrumental variable (IV) methods are used to estimate causal effects in settings with unobserved confounding, where we cannot directly experiment on the treatment variable. Instruments are variables which only affect the outcome indirectly via the treatment variable(s). Most IV applications focus on low-dimensional treatments and crucially require at least as many instruments as treatments. This assumption is restrictive: in the natural sciences we often seek to infer causal effects of high-dimensional treatments (e.g., the effect of gene expressions or microbiota on health and disease), but can only run few experiments with a limited number of instruments (e.g., drugs or antibiotics). In such underspecified problems, the full treatment effect is not identifiable in a single experiment even in the linear case. We show that one can still reliably recover the projection of the treatment effect onto the instrumented subspace and develop techniques to consistently combine such partial estimates from different sets of instruments. We then leverage our combined estimators in an algorithm that iteratively proposes the most informative instruments at each round of experimentation to maximize the overall information about the full causal effect. 
slides: ""
url_pdf: ""
publication_types:
  - "3"
authors:
  - Elisabeth Ailer, Jason Hartford, Niki Kilbertus
summary: ""
#url_dataset: https://github.com/wowchemy/wowchemy-hugo-themes
#url_project: ""
#author_notes: []
publication_short: ""
url_source: https://arxiv.org/abs/2302.05684
#url_video: https://youtube.com
publication: arxiv Preprint
#featured: false
date: 2023-02-11T00:00:00.000Z
#url_slides: ""
title: Sequential Underspecified Instrument Selection for Cause-Effect Estimation
tags:
  - [Instrumental Variables, Causality]
projects: []
image:
  caption: ""
  focal_point: ""
  preview_only: false
  filename: null
publishDate: 2023-02-11T00:00:00.000Z
# url_poster: ""
url_code: https://github.com/EAiler/underspecified-iv
#doi: 2106.11234
---
