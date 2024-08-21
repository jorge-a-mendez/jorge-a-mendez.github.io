---
layout: 'publication'
title: "Improving Black-box Robustness with In-Context Rewriting"
collection: publications
type: 'journal'
permalink: /publication/2024-in-context-rewriting
excerpt: 'We propose a test-time augmentation approach that leverages LLMs to transform out-of-distribution data into in-distribution to improve robustness of task-specific natural language classifiers.'
date: 2024-08-04
venue: 'Transactions on Machine Learning Research (TMLR)'
paperurl: 'https://arxiv.org/pdf/2402.08225'
authors: "Kyle O'Brien and Nathan Hoyen Ng and Isha Puri and <strong>Jorge Mendez-Mendez</strong> and Hamid Palangi and Yoon Kim and Marzyeh Ghassemi and Thomas Hartvigsen"
thumbnail: 'TTA_Intro_Figure-1.png'
abstract: "Machine learning models often excel on in-distribution (ID) data but struggle with unseen out-of-distribution (OOD) inputs. Most techniques for improving OOD robustness are not applicable to settings where the model is effectively a black box, such as when the weights are frozen, retraining is costly, or the model is leveraged via an API. Test-time augmentation (TTA) is a simple post-hoc technique for improving robustness that sidesteps black-box constraints by aggregating predictions across multiple augmentations of the test input. TTA has seen limited use in NLP due to the challenge of generating effective natural language augmentations. In this work, we propose LLM-TTA, which uses LLM-generated augmentations as TTA's augmentation function. LLM-TTA outperforms conventional augmentation functions across sentiment, toxicity, and news classification tasks for BERT and T5 models, with BERT's OOD robustness improving by an average of 4.30 percentage points without regressing average ID performance. We explore selectively augmenting inputs based on prediction entropy to reduce the rate of expensive LLM augmentations, allowing us to maintain performance gains while reducing the average number of generated augmentations by 57.76%. LLM-TTA is agnostic to the task model architecture, does not require OOD labels, and is effective across low and high-resource settings. We share our data, models, and code for reproducibility."
bibtex: "@article{obrien2024improving,
<br> author = {Kyle O'Brien and Nathan Hoyen Ng and Isha Puri and Jorge Mendez-Mendez and Hamid Palangi and Yoon Kim and Marzyeh Ghassemi and Thomas Hartvigsen},
<br> journal = {Transactions on Machine Learning Research (TMLR)},
<br> title = {Improving Black-box Robustness with In-Context Rewriting},
<br> year = {2024}
<br>}"
