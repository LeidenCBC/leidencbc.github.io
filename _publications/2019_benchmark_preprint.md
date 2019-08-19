---
layout: publication
title: "A comparison of automatic cell identification methods for single-cell RNA-sequencing data"
key: 2019_benchmark_preprint
date:   2019-05-20 00:00:00
permalink: /publications/2019_benchmark_preprint/
type: preprint

shortname: single cell classification benchmark

image: 2019_benchmark_preprint.png
image_large: 2019_benchmark_preprint_teaser.png


authors:
- abdelaal
- michielsen
- Davy Cats
- Dylan Hoogduin
- Hailiang Mei
- reinders
- mahfouz

journal: BioRxiv
journal-short: BioRxiv
page_start:
page_end:
chapter:
volume:
issue:
year: 2019
editor:
publisher:
school:
award:

doi: 10.1101/644435

projects:
external-project:

videos:

pdf: 2019_benchmark_preprint.pdf

supplements:

abstract: "Background Single cell transcriptomics are rapidly advancing our understanding of the cellular composition of complex tissues and organisms. A major limitation in most analysis pipelines is the reliance on manual annotations to determine cell identities, which are time-consuming and irreproducible. The exponential growth in the number of cells and samples has prompted the adaptation and development of supervised classification methods for automatic cell identification.

Results Here, we benchmarked 20 classification methods that automatically assign cell identities including single cell-specific and general-purpose classifiers. The methods were evaluated using eight publicly available single cell RNA-sequencing datasets of different sizes, technologies, species, and complexity. The performance of the methods was evaluated based on their accuracy, percentage of unclassified cells, and computation time. We further evaluated their sensitivity to the input features, their performance across different annotation levels and datasets. We found that most classifiers performed well on a variety of datasets with decreased accuracy for complex datasets with overlapping classes or deep annotations. The general-purpose SVM classifier has overall the best performance across the different experiments.

Conclusions We present a comprehensive evaluation of automatic cell identification methods for single cell RNA-sequencing data. All the code used for the evaluation is available on GitHub (https://github.com/tabdelaal/scRNAseq_Benchmark). Additionally, we provide a Snakemake workflow to facilitate the benchmarking and to support extension of new methods and new datasets (https://github.com/tabdelaal/scRNAseq_Benchmark/tree/snakemake_and_docker)."

---
