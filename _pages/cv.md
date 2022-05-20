---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

See the PDF version [here](/files/CVJorgeAMendez.pdf).

{% include base_path %}

Education
======
* Ph.D. in Computer and Information Science, University of Pennsylvania, 2022
* M.S.E. in Robotics, University of Pennsylvania, 2018
* B.S. in Eletronics Engineering, Universidad Simon Bolivar (Venezuela), 2016

Research experience
======

* Summer 2022: Postdoctoral Researcher
  * GRASP Lab, University of Pennsylvania
  * Topics: lifelong learning, reinforcement learning, compositionality
  * Supervisor: [Eric Eaton](https://seas.upenn.edu/~eeaton)

* 2016-2022: Research Assistant
  * GRASP Lab, University of Pennsylvania
  * Topics: lifelong learning, reinforcement learning, compositionality
  * Supervisor: [Eric Eaton](https://seas.upenn.edu/~eeaton)

* Summer 2021: Research Intern
  * Facebook AI Research, NYC
  * Topics: mixture of experts models
  * Supervisor: [Arthur Szlam](https://scholar.google.com/citations?user=u3-FxUgAAAAJ&hl=en) and [Ludovic Denoyer](http://www-connex.lip6.fr/~denoyer/wordpress/)

* Summer 2020: Research Intern
  * Microsoft Research, Montreal
  * Topics: lifelong learning, reinforcement learning, compositionality
  * Supervisor: [Harm van Seijen](https://www.microsoft.com/en-us/research/people/havansei/)

* Summer 2019: Research Intern
  * Facebook AI
  * Topics: conversational AI, reinforcement learning, multidomain learning
  * Supervisor: [Alborz Geramifard](http://alborz-geramifard.com/Homepage/Welcome.html) and [Mohammad Ghavamzadeh](http://chercheurs.lille.inria.fr/~ghavamza/my_website/About_Me.html)
  

Publications
======

Preprints
-----
  <ul>{% for post in site.publications reversed %}
    {% if post.type == 'preprint' %}
      {% include archive-single-publication-cv.html %}
    {% endif %}
  {% endfor %}</ul>
  
Conference Papers
-----
  <ul>{% for post in site.publications reversed %}
    {% if post.type == 'conference' %}
      {% include archive-single-publication-cv.html %}
    {% endif %}
  {% endfor %}</ul>

Workshop Papers
-----
  <ul>{% for post in site.publications reversed %}
    {% if post.type == 'workshop' %}
      {% include archive-single-publication-cv.html %}
    {% endif %}
  {% endfor %}</ul>

<!-- Talks
======
  <ul>{% for post in site.talks %}
    {% include archive-single-talk-cv.html %}
  {% endfor %}</ul>
   -->

Teaching
======

University of Pennsylvania
------
  <ul>{% for post in site.teaching reversed %}
    {% if post.venue == "University of Pennsylvania" %}
      {% include archive-single-teaching-cv.html %}
    {% endif %}
  {% endfor %}</ul>
  
Universidad Simon Bolivar
------
  <ul>{% for post in site.teaching reversed %}
    {% if post.venue == "Universidad Simon Bolivar" %}
      {% include archive-single-teaching-cv.html %}
    {% endif %}
  {% endfor %}</ul>

Service and leadership
======

Conference Paper Reviewing
----
* ICML, International Conference on Machine Learning (2021<sup>\*</sup>)
* ICLR, International Conference on Learning Representations (2021<sup>\*</sup>, 2022<sup>\*</sup>)
* NeurIPS, Conference on Neural Information Processing Systems (2020, 2021<sup>\*</sup>)
* ICRA / RA-L, International Conference on Robotics and Automation (2020, 2021)
* Conference paper co-reviewer:
  * IJCAI, International Joint Conference on Artificial Intelligence (2017, 2018, 2019)
  * ICML, International Conference on Machine Learning (2018)
  * NeurIPS, Neural Information Processing Systems (2018)
  * AAAI, Conference on Artificial Intelligence (2019)

<sup>\*</sup>Outstanding reviewer

Workshop Proposal Reviewing
----
* AAAI, Conference on Artificial Intelligence (2021)