---
layout: publication
title: "Predicting cell populations in single cell mass cytometry data"
key: 2018_cytof_classification
date:   2019-03-12 00:00:00
permalink: /publications/2018_cytof_classification/
type: article

shortname: CyTOF Classification

image: 2018_cytof_classification.png
image_large: 2018_cytof_classification_teaser.png


# Authors in the "database" can be used with just the key (lastname). Others can be written properly.
authors:
- abdelaal
- vanunen
- hollt
- koning
- reinders
- mahfouz


journal: Cytometry Part A
journal-short: Cytometry A
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

doi: 10.1002/cyto.a.23738
publisher-url:

project:
external-project:

videos:

pdf: 2018_cytof_classification.pdf

supplements:
code: https://github.com/tabdelaal/CyTOF-Linear-Classifier

abstract: "Mass cytometry (CyTOF) is a valuable technology for high-dimensional analysis at the single cell level. Identification of different cell populations is an important task during the data analysis. Many clustering tools can perform this task, however, they are time consuming, often involve a manual step, and lack reproducibility when new data is included in the analysis. Learning cell types from an annotated set of cells solves these problems. However, currently available mass cytometry classifiers are either complex, dependent on prior knowledge of the cell type markers during the learning process, or can only identify canonical cell types. We propose to use a Linear Discriminant Analysis (LDA) classifier to automatically identify cell populations in CyTOF data. LDA shows comparable results with two state-of-the-art algorithms on four benchmark datasets and also outperforms a non-linear classifier such as the k-nearest neighbour classifier. To illustrate its scalability to large datasets with deeply annotated cell subtypes, we apply LDA to a dataset of ~3.5 million cells representing 57 cell types. LDA has high performance on abundant cell types as well as the majority of rare cell types, and provides accurate estimates of cell type frequencies. Further incorporating a rejection option, based on the estimated posterior probabilities, allows LDA to identify cell types that were not encountered during training. Altogether, reproducible prediction of cell type compositions using LDA opens up possibilities to analyse large cohort studies based on mass cytometry data."

---
