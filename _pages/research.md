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

<div style="font-size: 0.85em;">

{% for category in site.publication_category  %}
  {% assign category_posts = site.publications | where: "category", category[0] %}
  {% if category_posts.size > 0 %}
### {{ category[1].title }}
    {% for post in category_posts reversed %}
<div style="margin-bottom: 1em; padding-left: 1em; border-left: 3px solid #e1e4e8;">
  <strong><a href="{{ post.url }}">{{ post.title }}</a></strong><br>
  <em>{{ post.venue }}</em>, {{ post.date | date: "%Y" }}<br>
  {% if post.excerpt %}<span style="color: #666;">{{ post.excerpt }}</span>{% endif %}
</div>
    {% endfor %}
  {% endif %}
{% endfor %}

</div>
