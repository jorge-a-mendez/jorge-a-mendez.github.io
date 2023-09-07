---
layout: 'publication'
title: "Robotic Manipulation Datasets for Offline Compositional Reinforcement Learning"
collection: publications
type: 'workshop'
permalink: /publication/2022-composuite-offline
excerpt: 'We propose and release a variety of data sets for compositional off-line RL on CompoSuite'
date: 2022-12-15
venue: 'CoRL Workshop on Pre-training Robot Learning'
paperurl: 'https://openreview.net/pdf?id=UgH4qZd2eFs'
authors: 'Marcel Hussing<sup>&ast;</sup>, <strong>Jorge Mendez-Mendez</strong><sup>&ast;</sup>,  <a href="https://dekent.github.io">Cassandra Kent</a>, <a href="https://seas.upenn.edu/~eeaton/">Eric Eaton</a>'
codeurl: 'https://github.com/Lifelong-ML/CompoSuite.git'
abstract: 'Offline reinforcement learning (RL) is a promising direction that allows RL agents to be pre-trained from large datasets avoiding recurrence of expensive data collection. To advance the field, it is crucial to generate large-scale datasets. Compositional RL is particularly appealing for generating such large datasets, since 1) it permits creating many tasks from few components, and 2) the task structure may enable trained agents to solve new tasks by combining relevant learned components. This paper provides four offline RL datasets for simulated robotic manipulation created using the 256 tasks from CompoSuite. Each dataset is collected from an agent with a different degree of performance, and consists of 256 million transitions. We provide training and evaluation settings for assessing an agent’s ability to learn compositional task policies. Our benchmarking experiments on each setting show that current offline RL methods can learn the training tasks to some extent, but are unable to extract their compositional structure to generalize to unseen tasks, showing a need for further research in offline compositional RL.'
bibtex: '@inproceedings{mendez2022composuite,
<br> author = {Hussing, Marcel and Mendez-Mendez, Jorge and Kent, Cassandra and Eaton, Eric},
<br> booktitle = {CoRL 2022 Workshop on Pre-training Robot Learning},
<br> title = {Robotic Manipulation Datasets for Offline Compositional Reinforcement Learning},
<br> year = {2022}
<br>}'
---
