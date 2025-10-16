---
layout: 'publication'
title: "A Systematic Study of Large Language Models for Task and Motion Planning With PDDLStream"
collection: publications
type: 'preprint'
permalink: /publication/2025-systematic-study-of-llms-for-tamp
excerpt: 'We conduct a large-scale evaluation of LLMs applied to TAMP problems using a base PDDLStream planner as a verifier. We find the the LLM-based planners are on average less successful and slower than engineered baselines.'
date: 2025-09-30
paperurl: 'https://arxiv.org/pdf/2510.00182'
authors: '<strong>Jorge Mendez-Mendez</strong>'
thumbnail: 'LLM-PDDLStream-Combinatorial.png'
abstract: 'Using large language models (LLMs) to solve complex robotics problems requires understanding their planning capabilities. Yet while we know that LLMs can plan on some problems, the extent to which these planning capabilities cover the space of robotics tasks is unclear. One promising direction is to integrate the semantic knowledge of LLMs with the formal reasoning of task and motion planning (TAMP). However, the myriad of choices for how to integrate LLMs within TAMP complicates the design of such systems. We develop 16 algorithms that use Gemini 2.5 Flash to substitute key TAMP components. Our zero-shot experiments across 4,950 problems and three domains reveal that the Gemini-based planners exhibit lower success rates and higher planning times than their engineered counterparts. We show that providing geometric details increases the number of task-planning errors compared to pure PDDL descriptions, and that (faster) non-reasoning LLM variants outperform (slower) reasoning variants in most cases, since the TAMP system can direct the LLM to correct its mistakes.'
bibtex: "@article{mendez2025systematic,
    <br> author = {Mendez-Mendez, Jorge},
    <br> journal = {arXiv preprint arXiv:2510.00182},
    <br> title = {A Systematic Study of Large Language Models for Task and Motion Planning With {PDDLStream}},
    <br> year = {2025},
    <br>}"
---