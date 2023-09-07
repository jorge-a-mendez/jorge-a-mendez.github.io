---
layout: 'publication'
title: "Transfer Learning via Minimizing the Performance Gap Between Domains"
collection: publications
type: 'conference'
permalink: /publication/2019-transfer-learning-performance-gap
excerpt: 'We introduced the notion of performance gap as a label-dependent notion of domain discrepancy, and developed an boosting-based algorithm, gapBoost, that exploits the insights from gap minimization.'
date: 2019-12-01
venue: 'Advances in Neural Information Processing Systems (NeurIPS)'
paperurl: 'https://papers.nips.cc/paper/9249-transfer-learning-via-minimizing-the-performance-gap-between-domains.pdf'
authors: '<a href="https://sites.google.com/site/borriewang/">Boyu Wang</a>, <strong>Jorge Mendez-Mendez</strong>, Mingbo Cai, <a href="https://seas.upenn.edu/~eeaton/">Eric Eaton</a>'
thumbnail: 'GapBoost.jpg'
codeurl: 'https://github.com/bwang-ml/gapBoost.git'
posterurl: 'https://drive.google.com/file/d/16y3gtQTi3eldU-okSAScyE908HlzAhR3/view'
abstract: 'We propose a new principle for transfer learning, based on a straightforward intuition: if two domains are similar to each other, the model trained on one domain should also perform well on the other domain, and vice versa. To formalize this intuition, we define the performance gap as a measure of the discrepancy between the source and target domains. We derive generalization bounds for the instance weighting approach to transfer learning, showing that the performance gap can be viewed as an algorithm-dependent regularizer, which controls the model complexity. Our theoretical analysis provides new insight into transfer learning and motivates a set of general, principled rules for designing new instance weighting schemes for transfer learning. These rules lead to gapBoost, a novel and principled boosting approach for transfer learning. Our experimental evaluation on benchmark data sets shows that gapBoost significantly outperforms previous boosting-based transfer learning algorithms.'
bibtex: '@inproceedings{wang2019transfer,
 <br> author = {Wang, Boyu and Mendez-Mendez, Jorge and Cai, Mingbo and Eaton, Eric},
 <br> booktitle = {Advances in Neural Information Processing Systems 32 (NeurIPS)},
 <br> title = {Transfer Learning via Minimizing the Performance Gap Between Domains},
 <br> year = {2019}
<br> }'
---
