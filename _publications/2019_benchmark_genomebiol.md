---
layout: publication
title: "A comparison of automatic cell identification methods for single-cell RNA-sequencing data"
key: 2019_benchmark_genomebiol
date:   2019-09-09 00:00:00
permalink: /publications/2019_benchmark_genomebiol/
redirect_from: /publications/2019_benchmark_preprint/
type: article

shortname: single cell classification benchmark

image: 2019_benchmark_genomebiol.png
image_large: 2019_benchmark_genomebiol.png


authors:
- abdelaal
- michielsen
- Davy Cats
- Dylan Hoogduin
- Hailiang Mei
- reinders
- mahfouz

journal: Genome Biology
journal-short: Genome Biol
page_start:
page_end:
chapter:
volume: 20
issue: 1
year: 2019
editor:
publisher:
school:
award:

doi: 10.1186/s13059-019-1795-z

projects:
external-project:

videos:

pdf: 2019_benchmark_preprint.pdf

supplements:

code: https://github.com/tabdelaal/scRNAseq_Benchmark

abstract: "<br><strong>Background</strong> Single-cell transcriptomics is rapidly advancing our understanding of the cellular composition of complex tissues and organisms. A major limitation in most analysis pipelines is the reliance on manual annotations to determine cell identities, which are time-consuming and irreproducible. The exponential growth in the number of cells and samples has prompted the adaptation and development of supervised classification methods for automatic cell identification.
<br>
<br><strong>Results</strong>
Here, we benchmarked 22 classification methods that automatically assign cell identities including single-cell-specific and general-purpose classifiers. The performance of the methods is evaluated using 27 publicly available single-cell RNA sequencing datasets of different sizes, technologies, species, and levels of complexity. We use 2 experimental setups to evaluate the performance of each method for within dataset predictions (intra-dataset) and across datasets (inter-dataset) based on accuracy, percentage of unclassified cells, and computation time. We further evaluate the methods’ sensitivity to the input features, number of cells per population, and their performance across different annotation levels and datasets. We find that most classifiers perform well on a variety of datasets with decreased accuracy for complex datasets with overlapping classes or deep annotations. The general-purpose support vector machine classifier has overall the best performance across the different experiments.
<br>
<br><strong>Conclusions</strong>
We present a comprehensive evaluation of automatic cell identification methods for single-cell RNA sequencing data. All the code used for the evaluation is available on GitHub (https://github.com/tabdelaal/scRNAseq_Benchmark). Additionally, we provide a Snakemake workflow to facilitate the benchmarking and to support the extension of new methods and new datasets."

---
