---
title: "Phyloformer: towards fast and accurate phylogeny estimation with self-attention networks"
authors:
- luca
- Bastien Boussau
- admin
date: "2022"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2022-04-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["3"]

# Publication name and optional abbreviated publication name.
publication: "bioRxiv"
publication_short: ""

abstract: An important problem in molecular evolution is that of phylogenetic reconstruction, that is, given a set of sequences descending from a common ancestor, the reconstruction of the binary tree describing their evolution from the latter. State-of-the-art methods for the task, namely Maximum likelihood and Bayesian inference, have a high computational cost, which limits their usability on large datasets. Recently researchers have begun investigating deep learning approaches to the problem but so far these attempts have been limited to the reconstruction of quartet tree topologies, addressing phylogenetic reconstruction as a classification problem. We present here a radically different approach with a transformer-based network architecture that, given a multiple sequence alignment, predicts all the pairwise evolutionary distances between the sequences, which in turn allow us to accurately reconstruct the tree topology with standard distance-based algorithms. The architecture and its high degree of parameter sharing allow us to apply the same network to alignments of arbitrary size, both in the number of sequences and in their length. We evaluate our network Phyloformer on two types of simulations and find that its accuracy matches that of a Maximum Likelihood method on datasets that resemble training data, while being significantly faster.

# Summary. An optional shortened abstract.
summary: W﻿e train neural networks on sets of homologous sequences simulated from probabilistic evolution models to infer phylogenetic trees. We use self-attention to obtain permutation-equivariant functions and ensure that the obtained tree does not depend on the order in which the sequences are provided. Our hope is to perform inference that is order of magnitude faster than state of the art maximum likelihood, and as accurate or even better under models with untractable likelihoods.

# tags:
# - Source Themes
featured: false

links:
url_code: 'https://github.com/lucanest/Phyloformer'
url_pdf: 'https://www.biorxiv.org/content/10.1101/2022.06.24.496975v1'
url_video: 'https://www.youtube.com/watch?v=ytqRFZDg1vI'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Image credit: Laurent Jacob'
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
# projects:
# - Phyloformer

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: example
---
