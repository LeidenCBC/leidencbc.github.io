---
layout: publication
title: "SCHNEL: Scalable clustering of high dimensional single-cell data"
key: 2020_schnel_preprint
date:   2020-03-31 00:00:00
permalink: /publications/2020_schnel_preprint/
type: preprint

shortname: SCHNEL

image: schnel.png
image_large:


authors:
- abdelaal
- deRaadt
- Lelieveldt
- reinders
- mahfouz

journal: BioRxiv
journal-short: BioRxiv
page_start:
page_end:
chapter:
volume:
issue:
year: 2020
editor:
publisher:
school:
award:

doi:
publisher-url: https://www.biorxiv.org/content/10.1101/2020.03.30.015925v1

projects:
external-project:

videos:

pdf:

supplements:

code: https://github.com/paulderaadt/HSNE-clustering

abstract: "Motivation Single cell data measures multiple cellular markers at the single-cell level for thousands to millions of cells. Identification of distinct cell populations is a key step for further biological understanding, usually performed by clustering this data. Dimensionality reduction based clustering tools are either not scalable to large datasets containing millions of cells, or not fully automated requiring an initial manual estimation of the number of clusters. Graph clustering tools provide automated and reliable clustering for single cell data, but suffer heavily from scalability to large datasets.

Results We developed SCHNEL, a scalable, reliable and automated clustering tool for high-dimensional single-cell data. SCHNEL transforms large high-dimensional data to a hierarchy of datasets containing subsets of data points following the original data manifold. The novel approach of SCHNEL combines this hierarchical representation of the data with graph clustering, making graph clustering scalable to millions of cells. Using seven different cytometry datasets, SCHNEL outperformed three popular clustering tools for cytometry data, and was able to produce meaningful clustering results for datasets of 3.5 and 17.2 million cells within workable timeframes. In addition, we show that SCHNEL is a general clustering tool by applying it to single-cell RNA sequencing data, as well as a popular machine learning benchmark dataset MNIST.

Availability and Implementation: Implementation is available on GitHub (https://github.com/paulderaadt/HSNE-clustering)"

---
