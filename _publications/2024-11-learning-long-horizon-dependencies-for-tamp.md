---
layout: 'publication'
title: "Learning Long-Horizon Action Dependencies in Sampling-Based Bilevel Planning"
collection: publications
type: 'conference'
permalink: /publication/2024-learning-long-horizon-dependencies-for-tamp
excerpt: 'We learn a heuristic to optimize backtracking in sampling-based approaches to Task and Motion Planning, by looking ahead at future actions in a task plan before making decisions about how to parameterize the current action.'
date: 2023-11-06
venue: 'Conference on Robot Learning (CoRL)'
paperurl: 'https://openreview.net/pdf?id=DsFQg0G4Xu'
authors: 'Bartlomiej Cieslar, <a href="http://people.csail.mit.edu/lpk/">Leslie Kaelbling</a>, <a href="http://people.csail.mit.edu/tlp/">Tomas Lozano-Perez</a>, and <strong>Jorge Mendez-Mendez</strong>'
thumbnail: 'LongHorizonTAMP.png'
abstract: 'Autonomous robots will need the ability to make task and motion plans that involve long sequences of actions, e.g. to prepare a meal. One challenge is that the feasibility of actions late in the plan may depend on much earlier actions. This issue is exacerbated if these dependencies exist at a purely geometric level, making them difficult to express for a task planner. Backtracking is a common technique to resolve such geometric dependencies, but its time complexity limits its applicability to short-horizon dependencies. We propose an approach to account for these dependencies by learning a search heuristic for task and motion planning. We evaluate our approach on five quasi-static simulated domains and show a substantial improvement in success rate over the baselines.'
bibtex: "@inproceedings{cieslar2024learning,
    <br> author = {Cieslar, Bartlomiej and Kaelbling, Leslie Pack and Lozano-Perez, Tomas and Mende-Mendez, Jorge},
    <br> booktitle = {Proceedings of the 8th Conference on Robot Learning (CoRL-24)},
    <br> title = {Learning Long-Horizon Action Dependencies in Sampling-Based Bilevel Planning},
    <br> year = {2024},
    <br>}"
---