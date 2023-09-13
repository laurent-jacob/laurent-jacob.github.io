---
title: "CALDERA: Finding all significant de Bruijn subgraphs for bacterial GWAS"
authors:
- Hector Roux de Bézieux
- Leandro Lima
- Fanny Perraudeau
- Arnaud Mary
- Sandrine Dudoit
- admin
date: "2022"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2022-07-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "Intelligent Systems for Molecular Biology"
publication_short: "ISMB"

abstract: Genome-wide association studies (GWAS), aiming to find genetic variants associated with a trait, have widely been used on bacteria to identify genetic determinants of drug resistance or hypervirulence. Recent bacterial GWAS methods usually rely on k-mers, whose presence in a genome can denote variants ranging from singlenucleotide polymorphisms to mobile genetic elements. This approach does not require a reference genome, making it easier to account for accessory genes. However, a same gene can exist in slightly different versions across different strains, leading to diluted effects. Here, we overcome this issue by testing covariates built from closed connected subgraphs (CCSs) of the de Bruijn graph defined over genomic k-mers. These covariates capture polymorphic genes as a single entity, improving k-mer-based GWAS both in terms of power and interpretability. However, a method naively testing all possible subgraphs would be powerless due to multiple testing corrections, and the mere exploration of these subgraphs would quickly become computationally intractable. The concept of testable hypothesis has successfully been used to address both problems in similar contexts. We leverage this concept to test all CCSs by proposing a novel enumeration scheme for these objects which fully exploits the pruning opportunity offered by testability, resulting in drastic improvements in computational efficiency. Our method integrates with existing visual tools to facilitate interpretation.

# Summary. An optional shortened abstract.
summary: A follow-up on DBGWAS. We use the structure of the de Bruijn graph to define new genomic variants (e.g. gene presence) that accomodate polymorphisms. This amounts to defining one variant for each connected subgraph. We rely on a reverse search strategy to efficiently enumerate variants, and on the Tarone strategy to control the FWER when testing their association with a bacterial phenotype.

# tags:
# - Source Themes
featured: false

# links:
# - name: ""
#   url: ""
url_code: 'https://hectorrdb.github.io/project/caldera/'
url_pdf: 'https://academic.oup.com/bioinformatics/article/38/Supplement_1/i36/6617517'
url_video: 'https://www.youtube.com/watch?v=0AY8KBVDkCQ'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Image credit: Hector Roux de Bézieux'
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
# projects: [caldera]

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: example
---
