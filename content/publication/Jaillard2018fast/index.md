---
title: "A fast and agnostic method for bacterial genome-wide association studies: Bridging the gap between k-mers and genetic events"
authors:
- magali
- Leandro Lima
- Maud Tournoud
- Pierre Mahé
- Alex van Belkum
- Vincent Lacroix
- admin
date: "2018"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2018-11-12T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "PLOS Genetics"
# publication_short: "TMLR"

abstract: Genome-wide association study (GWAS) methods applied to bacterial genomes have shown promising results for genetic marker discovery or detailed assessment of marker effect. Recently, alignment-free methods based on k-mer composition have proven their ability to explore the accessory genome. However, they lead to redundant descriptions and results which are sometimes hard to interpret. Here we introduce DBGWAS, an extended k-mer-based GWAS method producing interpretable genetic variants associated with distinct phenotypes. Relying on compacted De Bruijn graphs (cDBG), our method gathers cDBG nodes, identified by the association model, into subgraphs defined from their neighbourhood in the initial cDBG. DBGWAS is alignment-free and only requires a set of contigs and phenotypes. In particular, it does not require prior annotation or reference genomes. It produces subgraphs representing phenotype-associated genetic variants such as local polymorphisms and mobile genetic elements (MGE). It offers a graphical framework which helps interpret GWAS results. Importantly it is also computationally efficient—experiments took one hour and a half on average. We validated our method using antibiotic resistance phenotypes for three bacterial species. DBGWAS recovered known resistance determinants such as mutations in core genes in Mycobacterium tuberculosis, and genes acquired by horizontal transfer in Staphylococcus aureus and Pseudomonas aeruginosa—along with their MGE context. It also enabled us to formulate new hypotheses involving genetic variants not yet described in the antibiotic resistance literature.

# Summary. An optional shortened abstract.
summary: W﻿e describe the variation in bacterial genomes through their content in short sequences (k-mers). This avoids the bias usually caused by focusing on pre-defined SNPs or gene lists. We use this representation to pinpoint the genomic variation associated to antimicrobial resitances, and rely on a so-called de Bruijn graph to help make sense of the identified k-mers in terms of SNPs or mobile genetic elements.

# tags:
# - Source Themes
featured: false

# links:
# - name: ""
#   url: ""
url_code: 'https://gitlab.com/leoisl/dbgwas'
url_pdf: 'https://pubmed.ncbi.nlm.nih.gov/30419019/'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Image credit: Magali Jaillard'
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
# projects: [dbgwas]

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: example
---
