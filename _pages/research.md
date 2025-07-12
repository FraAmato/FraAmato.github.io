---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---

## My Research Focus

My research focuses on clustering longitudinal mixed-type data, with applications in healthcare and social sciences.

## Current Projects

- Project 1: Description
- Project 2: Description

{% if site.author.googlescholar %}
You can also find my articles on [my Google Scholar profile]({{site.author.googlescholar}}).
{% endif %}

## Publications
{% include base_path %}

{% if site.publication_category %}
  {% for category in site.publication_category  %}
    {% assign title_shown = false %}
    {% for post in site.publications reversed %}
      {% if post.category != category[0] %}
        {% continue %}
      {% endif %}
      {% unless title_shown %}
### {{ category[1].title }}
        {% assign title_shown = true %}
      {% endunless %}
      {% include archive-single.html %}
    {% endfor %}
  {% endfor %}
{% else %}
  {% for post in site.publications reversed %}
    {% include archive-single.html %}
  {% endfor %}
{% endif %}
