---
layout: archive
title: "Teaching"
permalink: /teaching/
author_profile: true
---

{% include base_path %}

Stony Brook University
-----

{% for post in site.teaching reversed %}
  {% if post.venue == "Stony Brook University" %}
    {% include archive-single-teaching.html %}
  {% endif %}
{% endfor %}

University of Pennsylvania
-----

{% for post in site.teaching reversed %}
  {% if post.venue == "University of Pennsylvania" %}
    {% include archive-single-teaching.html %}
  {% endif %}
{% endfor %}

Universidad Simon Bolivar
-----

{% for post in site.teaching reversed %}
  {% if post.venue == "Universidad Simon Bolivar" %}
    {% include archive-single-teaching.html %}
  {% endif %}
{% endfor %}