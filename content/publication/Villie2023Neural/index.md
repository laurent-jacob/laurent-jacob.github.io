---
title: "Neural Networks beyond explainability: Selective inference for sequence motifs"
authors:
- antoine
- Philippe Veber
- Yohann de Castro
- admin
date: "2023"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2023-07-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "Transactions in Machine Learning Research"
publication_short: "TMLR"

abstract: Over the past decade, neural networks have been successful at making predictions from biological sequences. As in other fields of deep learning, tools have been devised to extract features such as sequence motifs that can explain the predictions made by a trained network. Here we intend to go beyond explainable machine learning and introduce SEISM, a selective inference procedure to test the association between these extracted features and the predicted phenotype. In particular, we discuss how training a one-layer convolutional network is formally equivalent to selecting motifs maximizing some association score. We adapt existing sampling-based selective inference procedures by quantizing this selection over an infinite set to a large but finite grid. Finally, we show that sampling under a specific choice of parameters is sufficient to characterize the composite null hypothesis typically used for selective inference—a result that goes well beyond our particular framework. We illustrate the behavior of our method in terms of calibration, power and speed and discuss its power/speed trade-off with a simpler data-split strategy. SEISM paves the way to an easier analysis of neural networks used in regulatory genomics, and to more powerful methods for genome wide association studies (GWAS).

# Summary. An optional shortened abstract.
summary: Convolutional neural networks on biological sequences are known to learn probabilistic motifs associated with the target phenotype. To go beyond this informal interpretation, we provide a statistical test quantifying the motif-phenotype association. This requires to solve a post-selection inference problem, where the selection involves the infinite set of possible motifs.

# tags:
# - Source Themes
featured: false

# links:
# - name: ""
#   url: ""
url_code: 'https://gitlab.in2p3.fr/antoine.villie1/seism'
url_pdf: 'https://openreview.net/pdf?id=nddEHTSnqg'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Image credit: Antoine Villie'
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
# projects: [seism]

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: example
---
