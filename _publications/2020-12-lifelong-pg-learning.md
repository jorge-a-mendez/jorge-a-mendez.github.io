---
layout: 'publication'
title: "Lifelong Policy Gradient Learning of Factored Policies for Faster Training Without Forgetting"
collection: publications
type: 'conference'
permalink: /publication/2020-lifelong-pg-learning
excerpt: 'We introduced an algorithm for directly optimizing factored policies via policy gradients in a lifelong learning setting, and showed theoretically and empirically that our approach avoids catastrophic forgetting.'
date: 2020-12-01
venue: 'Advances in Neural Information Processing Systems (NeurIPS)'
paperurl: 'https://arxiv.org/pdf/2007.07011.pdf'
authors: '<strong>Jorge A. Mendez</strong>, <a href="https://sites.google.com/site/borriewang/">Boyu Wang</a>, <a href="https://seas.upenn.edu/~eeaton/">Eric Eaton</a>'
thumbnail: 'LPG-FTW.jpg'
codeurl: 'https://github.com/Lifelong-ML/LPG-FTW.git'
abstract: 'Policy gradient methods have shown success in learning control policies for high-dimensional dynamical systems. Their biggest downside is the amount of exploration they require before yielding high-performing policies. In a lifelong learning setting, in which an agent is faced with multiple consecutive tasks over its lifetime, reusing information from previously seen tasks can substantially accelerate the learning of new tasks. We provide a novel method for lifelong policy gradient learning that trains lifelong function approximators directly via policy gradients, allowing the agent to benefit from accumulated knowledge throughout the entire training process. We show empirically that our algorithm learns faster and converges to better policies than single-task and lifelong learning baselines, and completely avoids catastrophic forgetting on a variety of challenging domains.'
bibtex: '@inproceedings{mendez2020lifelong,
 <br> author = {Mendez, Jorge A. and Wang, Boyu and Eaton, Eric},
 <br> booktitle = {Advances in Neural Information Processing Systems 33 (NeurIPS-20)},
 <br> pages = {14398--14409},
 <br> title = {Lifelong Policy Gradient Learning of Factored Policies for Faster Training Without Forgetting},
 <br> year = {2020}
<br>}'
---
