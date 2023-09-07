---
layout: 'publication'
title: "Robotic Manipulation Datasets for Offline Compositional Reinforcement Learning"
collection: publications
type: 'preprint'
permalink: /publication/2023-compositional-offline-rl-datasets
excerpt: 'We release four datasets of simulated robotic manipulation trajectories for offline compositional reinforcement learning.'
date: 2023-07-13
paperurl: 'https://arxiv.org/pdf/2307.07091.pdf'
authors: 'Marcel Hussing<sup>&ast;</sup>, <strong>Jorge Mendez-Mendez</strong><sup>&ast;</sup>, Anisha Singrodia, <a href="https://dekent.github.io">Cassandra Kent</a>, <a href="https://seas.upenn.edu/~eeaton/">Eric Eaton</a>'
thumbnail: 'OfflineComposuite.png'
codeurl: 'https://github.com/Lifelong-ML/offline-compositional-rl-datasets.git'
abstract: "Offline reinforcement learning (RL) is a promising direction that allows RL agents to pre-train on large datasets, avoiding the recurrence of expensive data collection. To advance the field, it is crucial to generate large-scale datasets. Compositional RL is particularly appealing for generating such large datasets, since 1) it permits creating many tasks from few components, 2) the task structure may enable trained agents to solve new tasks by combining relevant learned components, and 3) the compositional dimensions provide a notion of task relatedness. This paper provides four offline RL datasets for simulated robotic manipulation created using the 256 tasks from CompoSuite [Mendez et al., 2022a]. Each dataset is collected from an agent with a different degree of performance, and consists of 256 million transitions. We provide training and evaluation settings for assessing an agent's ability to learn compositional task policies. Our benchmarking experiments on each setting show that current offline RL methods can learn the training tasks to some extent and that compositional methods significantly outperform non-compositional methods. However, current methods are still unable to extract the tasks' compositional structure to generalize to unseen tasks, showing a need for further research in offline compositional RL."
bibtex: '@article{hussing2023robotic,
<br> author = {Hussing, Marcel and Mendez-Mendez, Jorge and Singrodia, Anisha and Kent, Cassandra and Eaton, Eric},
<br> journal = {arXiv preprint: arXiv:2307.07091},
<br> title = {Robotic Manipulation Datasets for Offline Compositional Reinforcement Learning},
<br> year = {2023}
<br>}'
---
