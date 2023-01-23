---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if site.author.googlescholar %}
  You can also find my articles on <u><a href="{{ site.author.googlescholar }}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

Preprints
-----

{% for post in site.publications reversed %}
  {% if post.type == 'preprint' %}
    {% include archive-single-publication.html %}
  {% endif %}
{% endfor %}

Journal Articles
-----

{% for post in site.publications reversed %}
  {% if post.type == 'journal' %}
    {% include archive-single-publication.html %}
  {% endif %}
{% endfor %}

Conference Papers
-----

{% for post in site.publications reversed %}
  {% if post.type == 'conference' %}
    {% include archive-single-publication.html %}
  {% endif %}
{% endfor %}

Workshop Papers
-----

{% for post in site.publications reversed %}
  {% if post.type == 'workshop' %}
    {% include archive-single-publication.html %}
  {% endif %}
{% endfor %}


Theses
-----

{% for post in site.publications reversed %}
  {% if post.type == 'thesis' %}
    {% include archive-single-publication.html %}
  {% endif %}
{% endfor %}
