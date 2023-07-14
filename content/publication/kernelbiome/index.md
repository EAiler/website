---
abstract: 
  Supervised learning, such as regression and classification, is an essential tool for analyzing modern high-throughput sequencing data, for example in microbiome research. However, due to the compositionality and sparsity, existing techniques are often inadequate. Either they rely on extensions of the linear log-contrast model (which adjust for compositionality but cannot account for complex signals or sparsity) or they are based on black-box machine learning methods (which may capture useful signals, but lack interpretability due to the compositionality).\
  We propose KernelBiome, a kernel-based nonparametric regression and classification framework for compositional data. It is tailored to sparse compositional data and is able to incorporate prior knowledge, such as phylogenetic structure.
  KernelBiome captures complex signals, including in the zero-structure, while automatically adapting model complexity. We demonstrate on par or improved predictive performance compared with state-of-the-art machine learning methods on $33$ publicly available microbiome datasets. Additionally, our framework provides two key advantages; (i) We propose two novel quantities to interpret contributions of individual components and prove that they consistently estimate average perturbation effects of the conditional mean, extending the interpretability of linear log-contrast coefficients to nonparametric models. (ii) 
  We show that the connection between kernels and distances aids interpretability and provides a data-driven embedding that can augment further analysis.
slides: ""
url_pdf: ""
publication_types:
  - "3"
authors:
  - Shimeng Huang, Elisabeth Ailer, Niki Kilbertus, Niklas Pfister
summary: ""
#url_dataset: https://github.com/wowchemy/wowchemy-hugo-themes
#url_project: ""
#author_notes: []
publication_short: ""
url_source: https://journals.plos.org/ploscompbiol/article?id=10.1371/journal.pcbi.1011240
#url_video: https://youtube.com
publication: 
#featured: false
date: 2023-06-11T00:00:00.000Z
#url_slides: ""
title: Supervised Learning and Model Analysis with Compositional Data
tags:
  - [Kernel Methods, Compositional Data]
projects: []
image:
  caption: ""
  focal_point: ""
  preview_only: false
  filename: null
publishDate: 2023-06-11T00:00:00.000Z
# url_poster: ""
url_code: https://github.com/shimenghuang/KernelBiome
#doi: 2106.11234
---
