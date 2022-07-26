---
layout: 'publication'
title: "Lifelong Machine Learning of Functionally Compositional Structures"
collection: publications
type: 'thesis'
permalink: /publication/2022-lifelong-machine-learning-of-functionally-compositional-structures
excerpt: 'This dissertation presents an in-depth treatment of the problems of lifelong or continual learning and compositional knowledge representations, which had so far been studied separately.'
date: 2022-04-22
venue: 'University of Pennsylvania'
paperurl: 'https://arxiv.org/pdf/2207.12256.pdf'
authors: '<strong>Jorge A. Mendez</strong>'
thumbnail: 'LifelongCompositionalLearning.jpg'
abstract: 'A hallmark of human intelligence is the ability to construct self-contained chunks of knowledge and reuse them in novel combinations for solving different yet structurally related problems. Learning such compositional structures has been a significant challenge for artificial systems, due to the underlying combinatorial search. To date, research into compositional learning has largely proceeded separately from work on lifelong or continual learning. This dissertation integrated these two lines of work to present a general-purpose framework for lifelong learning of functionally compositional structures. The framework separates the learning into two stages: learning how to best combine existing components to assimilate a novel problem, and learning how to adapt the set of existing components to accommodate the new problem. This separation explicitly handles the trade-off between the stability required to remember how to solve earlier tasks and the flexibility required to solve new tasks. This dissertation instantiated the framework into various supervised and reinforcement learning (RL) algorithms. Empirical evaluations on a range of supervised learning benchmarks compared the proposed algorithms against well-established techniques, and found that 1)~compositional models enable improved lifelong learning when the tasks are highly diverse by balancing the incorporation of new knowledge and the retention of past knowledge, 2)~the separation of the learning into stages permits lifelong learning of compositional knowledge, and 3)~the components learned by the proposed methods represent self-contained and reusable functions. Similar evaluations on existing and new RL benchmarks demonstrated that 1)~algorithms under the framework accelerate the discovery of high-performing policies in a variety of domains, including robotic manipulation, and 2)~these algorithms retain, and often improve, knowledge that enables them to solve tasks learned in the past. The dissertation extended one lifelong compositional RL algorithm to the nonstationary setting, where the distribution over tasks varies over time, and found that modularity permits individually tracking changes to different elements in the environment. The final contribution of this dissertation was a new benchmark for evaluating approaches to compositional RL, which exposed that existing methods struggle to discover the compositional properties of the environment.'
bibtex: '@phdthesis{mendez2022lifelong,
<br> author = {Mendez, Jorge A.},
<br> school = {University of Pennsylvania},
<br> title = {Lifelong Inverse Reinforcement Learning},
<br> year = {2012}
<br>}'
---
