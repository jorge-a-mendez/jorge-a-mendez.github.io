---
layout: 'publication'
title: "Continual Improvement of Threshold-Based Novelty Detection"
collection: publications
type: 'workshop'
permalink: /publication/2023-continual-improvement-of-novelty-detection
excerpt: 'We introduce a simple cross-validation-based procedure to automatically tune the threshold for continual novelty detection using SHELS.'
date: 2023-08-22
venue: 'CoLLAs Workshop Track'
paperurl: 'https://arxiv.org/pdf/2309.02551.pdf'
authors: 'Abe Ejilemele, <strong>Jorge Mendez-Mendez</strong>'
thumbnail: 'SHELS_exclusive_feature_sets.png'
abstract: 'When evaluated in dynamic, open-world situations, neural networks struggle to detect unseen classes. This issue complicates the deployment of continual learners in realistic environments where agents are not explicitly informed when novel categories are encountered. A common family of techniques for detecting novelty relies on thresholds of similarity between observed data points and the data used for training. However, these methods often require manually specifying (ahead of time) the value of these thresholds, and are therefore incapable of adapting to the nature of the data. We propose a new method for automatically selecting these thresholds utilizing a linear search and leave-one-out cross-validation on the ID classes. We demonstrate that this novel method for selecting thresholds results in improved total accuracy on MNIST, Fashion MNIST, and CIFAR-10.'
bibtex: "@inproceedings{ejilemele2023continual,
<br> author = {Ejilemele, Abe and Mendez-Mendez, Jorge},
<br> booktitle = {CoLLAs-23 Workshop Track},
<br> title = {Continual Improvement of Threshold-Based Novelty Detection},
<br> year = {2023}
<br>}"
---
