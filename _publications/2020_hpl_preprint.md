---
layout: publication
title: "Hierarchical progressive learning of cell identities in single-cell data"
key: 2020_hpl_preprint
date:   2020-03-29 00:00:00
permalink: /publications/2020_hpl_preprint/
type: preprint

shortname: Hierarchical progressive learning

image: 2020_hpl_preprint.png
image_large:


authors:
- michielsen
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
publisher-url: https://www.biorxiv.org/content/10.1101/2020.03.27.010124v1

projects:
external-project:

videos:

pdf: 2020_hpl_preprint.pdf

supplements: 2020_hpl_preprint_supplement.pdf

code: https://github.com/lcmmichielsen/hierarchicalprogressivelearning

abstract: "Motivation: In single-cell RNA-sequencing datasets, cell identification is mainly done manually, which is subjective and time-consuming. As a consequence, most datasets are annotated at a different resolution. This is not surprising as cell populations form a hierarchy, but it can be problematic for downstream analysis or comparison of datasets. Several supervised methods have been developed to overcome the drawbacks of unsupervised learning, but none of these combines the information of multiple datasets and preserves the old definition of the cell populations in each dataset.

Results: To overcome these challenges, we developed a hierarchical progressive learning method which automatically finds relationships between populations of multiple datasets and uses this to construct a classification tree. We implemented the tree with a one-class and linear SVM for each node and evaluated the classification performance, including the rejection option, and tree construction. At the moment, choosing between a one-class and linear SVM is a trade-off between the ability of discovering new cell populations and a higher accuracy. Both the one-class and linear SVM also outperform other hierarchical classifiers. Furthermore, we show that it is possible to construct a correct classification tree for immune cells when combining three PBMC datasets and predict the labels of the fourth dataset with high accuracy.

Availability and implementation: The pipeline is implemented in Python and available at Github (https://github.com/lcmmichielsen/hierarchicalprogressivelearning)."

---
