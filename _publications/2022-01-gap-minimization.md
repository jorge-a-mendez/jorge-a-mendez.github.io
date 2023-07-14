---
layout: 'publication'
title: "Gap Minimization for Knowledge Sharing and Transfer"
collection: publications
type: 'journal'
permalink: /publication/2023-gap-minimization
excerpt: 'We extended the notion of performance gap for measuring domain discrepancy (NeurIPS-19) to a variety of transfer and multi-task learning settings, and introduced two new algorithms based on this notion for improving transfer and multi-task learning performance.'
date: 2023-01-26
venue: 'Journal on Machine Learning Research (JMLR)'
paperurl: 'https://arxiv.org/pdf/2201.11231.pdf'
authors: '<a href="https://sites.google.com/site/borriewang/">Boyu Wang</a>, <strong>Jorge A. Mendez</strong>, <a href="https://cjshui.github.io">Changjian Shui</a>, <a href="https://fzhou.cc">Fan Zhou</a>, <a href="https://sites.google.com/view/di-wu/home?authuser=1"> Di Wu</a>, Xu, Gezheng, <a href="https://chgagne.github.io/english/">Christian Gagne</a>, <a href="https://seas.upenn.edu/~eeaton/">Eric Eaton</a>'
thumbnail: 'GapBoost.jpg'
abstract: 'Learning from multiple related tasks by knowledge sharing and transfer has become increasingly relevant over the last two decades. In order to successfully transfer information from one task to another, it is critical to understand the similarities and differences between the domains. In this paper, we introduce the notion of <i>performance gap</i>, an intuitive and novel measure of the distance between learning tasks. Unlike existing measures which are used as tools to bound the difference of expected risks between tasks (e.g., H-divergence or discrepancy distance), we theoretically show that the performance gap can be viewed as a data- and algorithm-dependent regularizer, which controls the model complexity and leads to finer guarantees. More importantly, it also provides new insights and motivates a novel principle for designing strategies for knowledge sharing and transfer: gap minimization. We instantiate this principle with two algorithms: 1. gapBoost, a novel and principled boosting algorithm that explicitly minimizes the performance gap between source and target domains for transfer learning; and 2. gapMTNN, a representation learning algorithm that reformulates gap minimization as semantic conditional matching for multitask learning. Our extensive evaluation on both transfer learning and multitask learning benchmark data sets shows that our methods outperform existing baselines.'
bibtex: "@article{wang2023gap,
<br> author = {Wang, Boyu and Mendez, Jorge A. and Shui, Changjian and Zhou, Fan and Wu, Di and Xu, Gezheng and Gagne, Christian and Eaton, Eric},
<br> journal = {Journal of Machine Learning Research},
<br> title = {Gap Minimization for Knowledge Sharing and Transfer},
<br> volume = {24},
<br> number = {33},
<br> pages = {1--57},
<br> year = {2023}
<br>}"
---
