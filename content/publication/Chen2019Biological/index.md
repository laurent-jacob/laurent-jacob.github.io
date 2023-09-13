---
title: "Biological sequence modeling with convolutional kernel networks"
authors:
- dexiong
- Julien Mairal
- admin
date: "2019"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2019-09-15T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "Bioinformatics"
# publication_short: ""

abstract: The growing number of annotated biological sequences available makes it possible to learn genotype-phenotype relationships from data with increasingly high accuracy. When large quantities of labeled samples are available for training a model, convolutional neural networks can be used to predict the phenotype of unannotated sequences with good accuracy. Unfortunately, their performance with medium- or small-scale datasets is mitigated, which requires inventing new data-efficient approaches. We introduce a hybrid approach between convolutional neural networks and kernel methods to model biological sequences. Our method enjoys the ability of convolutional neural networks to learn data representations that are adapted to a specific task, while the kernel point of view yields algorithms that perform significantly better when the amount of training data is small. We illustrate these advantages for transcription factor binding prediction and protein homology detection, and we demonstrate that our model is also simple to interpret, which is crucial for discovering predictive motifs in sequences.

# Summary. An optional shortened abstract.
summary: W﻿e analyze convolutional and recurrent neural networks for biological sequences in the framework of positive definite kernels. In addition to providing a new interpretation on the genomic features underlying these networks, this analysis provides a version that is better regularized and performs better when few data is available. We also extended this work to graph-structured data.

# tags:
# - Source Themes
featured: false

# links:
# - name: ""
#   url: ""
url_code: 'https://gitlab.inria.fr/dchen/CKN-seq'
url_pdf: 'https://academic.oup.com/bioinformatics/article/35/18/3294/5308597'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Image credit: Dexiong Chen'
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
# projects: [CKN]

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: example
---
