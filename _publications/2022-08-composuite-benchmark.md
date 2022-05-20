---
layout: 'publication'
title: "CompoSuite: A Compositional Reinforcement Learning Benchmark"
collection: publications
type: 'conference'
permalink: /publication/2022-composuite-benchmark
excerpt: 'We introduce CompoSuite, a robotic manipulation benchmark with hundreds of tasks for evaluating the functional compositionality of RL algorithms.'
date: 2022-08-01
venue: 'Conference on Lifelong Learning Agents (CoLLAs)'
authors: '<strong>Jorge A. Mendez</strong><sup>&ast;</sup>, Marcel Hussing<sup>&ast;</sup>, Meghna Gummadi, <a href="https://seas.upenn.edu/~eeaton/">Eric Eaton</a>'
abstract: 'We present CompoSuite, an open-source simulated robotic manipulation benchmark for compositional multi-task reinforcement learning (RL). Each CompoSuite task requires a particular _robot_ arm to manipulate one individual _object_ to achieve a task _objective_ while avoiding an _obstacle_. This compositional definition of the tasks endows CompoSuite with two remarkable properties. First, varying the robot/object/objective/obstacle elements leads to hundreds of RL tasks, each of which requires a meaningfully different behavior. Second, RL approaches can be evaluated specifically for their ability to learn the compositional structure of the tasks. This latter capability to functionally decompose problems would enable intelligent agents to identify and exploit commonalities between learning tasks to handle large varieties of highly diverse problems. We benchmark existing single-task, multi-task, and compositional learning algorithms on various training settings, and assess their capability to compositionally generalize to unseen tasks. Our evaluation exposes the shortcomings of existing RL approaches with respect to compositionality and opens new avenues for investigation.'
bibtex: '@inproceedings{mendez2022composuite,
<br> author = {Mendez, Jorge A and Hussing, Marcel and Gummadi, Meghna and Eaton, Eric},
<br> booktitle = {First Conference on Lifelong Learning Agents (CoLLAs-22)},
<br> title = {Compo{S}uite: A Compositional Reinforcement Learning Benchmark},
<br> year = {2022}
<br>}'
---
