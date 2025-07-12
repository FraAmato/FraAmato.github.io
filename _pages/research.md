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

<style>
.pub-item { 
  margin-bottom: 1.5em; 
  font-size: 0.9em; 
}
.pub-title { 
  font-weight: 600; 
  color: #2c3e50; 
}
.pub-venue { 
  color: #7f8c8d; 
  font-style: italic; 
}
</style>

{% for category in site.publication_category %}
  {% assign has_pubs = false %}
  {% for post in site.publications %}
    {% if post.category == category[0] %}
      {% unless has_pubs %}
### {{ category[1].title }}
        {% assign has_pubs = true %}
      {% endunless %}
<div class="pub-item">
  <div class="pub-title"><a href="{{ post.url }}">{{ post.title }}</a></div>
  <div class="pub-venue">{{ post.venue }}, {{ post.date | date: "%Y" }}</div>
</div>
    {% endif %}
  {% endfor %}
{% endfor %}
