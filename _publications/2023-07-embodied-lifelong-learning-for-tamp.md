---
layout: 'publication'
title: "Embodied Lifelong Learning for Task and Motion Planning"
collection: publications
type: 'conference'
permalink: /publication/2023-embodied-lifelong-learning-for-tamp
excerpt: 'We formulate a realistic variant of the problem of lifelong learning for TAMP, and devise a mixture of generative models for generating samples for efficient planning.'
date: 2023-07-13
venue: 'Conference on Robot Learning (CoRL)'
paperurl: 'https://arxiv.org/pdf/2307.06870.pdf'
authors: '<strong>Jorge Mendez-Mendez</strong>, <a href="http://people.csail.mit.edu/lpk/">Leslie Pack Kaelbling</a>, <a href="http://people.csail.mit.edu/tlp/">Tomas Lozano-Perez</a>'
thumbnail: 'LifelongTAMP.png'
abstract: 'A robot deployed in a home over long stretches of time faces a true lifelong learning problem. As it seeks to provide assistance to its users, the robot should leverage any accumulated experience to improve its own knowledge to become a more proficient assistant. We formalize this setting with a novel lifelong learning problem formulation in the context of learning for task and motion planning (TAMP). Exploiting the modularity of TAMP systems, we develop a generative mixture model that produces candidate continuous parameters for a planner. Whereas most existing lifelong learning approaches determine a priori how data is shared across task models, our approach learns shared and non-shared models and determines which to use online during planning based on auxiliary tasks that serve as a proxy for each model’s understanding of a state. Our method exhibits substantial improvements in planning success on simulated 2D domains and on several problems from the BEHAVIOR benchmark.'
bibtex: "@inproceedings{mendez2023embodied,
<br> author = {Mendez-Mendez, Jorge and Kaelbling, Leslie Pack and Lozano-Perez, Tomas},
<br> booktitle = {Proceedings of the 7th Conference on Robot Learning (CoRL-23)},
<br> title = {Embodied Lifelong Learning for Task and Motion Planning},
<br> year = {2023}
<br>}"
---
