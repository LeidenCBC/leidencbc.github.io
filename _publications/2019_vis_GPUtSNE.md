---
layout: publication
title: "GPGPU Linear Complexity t-SNE Optimization"
key: 2019_vis_GPUtSNE
date:   2019-08-01 12:00:00
permalink: /publications/2019_vis_GPUtSNE_teaser/
redirect_from: /publications/2018_arxiv_ttsne/
type: article
shortname: GPU t-SNE
image: 2019_vis_GPUtSNE.png
image_large: 2019_vis_GPUtSNE_teaser.png

authors:
- pezzotti
- Julian Thijssen
- Alexander Mordvintsev
- hollt
- Baldur van Lew
- lelieveldt
- eisemann
- vilanova

journal: IEEE Transactions on Visualization and Computer Graphics (Proceedings of IEEE VAST 2019)
journal-short: TVCG (VAST '19)
page_start:
page_end:
chapter:
volume: 26
issue: 1
year: 2020
editor:
publisher:
school:
award:

doi:
publisher-url:

projects:
external-project: https://nicola17.github.io/tfjs-tsne-demo/

videos:

pdf: 2019_vis_GPUtSNE.pdf
supplement:
supplements:
  - name: Python Executable
    abslink: https://github.com/biovault/nptsne
    icon: archive
code: https://github.com/biovault/High-Dimensional-Inspector

abstract: "In recent years the t-distributed Stochastic Neighbor Embedding (t-SNE) algorithm has become one of the most used and insightful techniques for exploratory data analysis of high-dimensional data. It reveals clusters of high-dimensional data points at different scales while only requiring minimal tuning of its parameters. However, the computational complexity of the algorithm limits its application to relatively small datasets. To address this problem, several evolutions of t-SNE have been developed in recent years, mainly focusing on the scalability of the similarity computations between data points. However, these contributions are insufficient to achieve interactive rates when visualizing the evolution of the t-SNE embedding for large datasets. In this work, we present a novel approach to the minimization of the t-SNE objective function that heavily relies on graphics hardware and has linear computational complexity. Our technique decreases the computational cost of running t-SNE on datasets by orders of magnitude and retains or improves on the accuracy of past approximated techniques. We propose to approximate the repulsive forces between data points by splatting kernel textures for each data point. This approximation allows us to reformulate the t-SNE minimization problem as a series of tensor operations that can be efficiently executed on the graphics card. An efficient implementation of our technique is integrated and available for use in the widely used Google TensorFlow.js, and an open-source C++ library."

---
