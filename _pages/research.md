---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---

<style>
.research-focus {
  background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
  color: white;
  padding: 25px;
  border-radius: 8px;
  margin: 30px 0;
}

.research-focus h2 {
  color: white;
  margin-top: 0;
  border-bottom: 2px solid rgba(255,255,255,0.3);
  padding-bottom: 10px;
}

.research-interests {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
  gap: 15px;
  margin: 25px 0;
}

.interest-card {
  background: linear-gradient(135deg, #74b9ff, #0984e3);
  color: white;
  padding: 20px;
  border-radius: 8px;
  text-align: center;
  transition: transform 0.2s ease;
}

.interest-card:hover {
  transform: translateY(-5px);
}

.interest-card h4 {
  margin-top: 0;
  margin-bottom: 10px;
  font-size: 1.1em;
}

.pub-item { 
  background: #f8f9ff;
  border-left: 4px solid #3498db;
  padding: 20px;
  margin: 15px 0;
  border-radius: 0 8px 8px 0;
  transition: transform 0.2s ease;
}

.pub-item:hover {
  transform: translateX(5px);
}

.pub-title { 
  font-weight: 600; 
  color: #2c3e50;
  font-size: 1.1em;
  margin-bottom: 8px;
}

.pub-title a {
  color: #2c3e50;
  text-decoration: none;
}

.pub-title a:hover {
  color: #3498db;
}

.pub-authors {
  color: #34495e;
  margin-bottom: 8px;
  font-size: 0.95em;
}

.pub-venue { 
  color: #7f8c8d; 
  font-style: italic;
  margin-bottom: 8px;
}

.pub-links {
  margin-top: 10px;
}

.doi-link, .hal-link {
  display: inline-block;
  padding: 4px 8px;
  border-radius: 4px;
  text-decoration: none;
  font-size: 0.85em;
  margin-right: 8px;
  margin-top: 5px;
}

.doi-link {
  background: #3498db;
  color: white;
}

.doi-link:hover {
  background: #2980b9;
  color: white;
}

.hal-link {
  background: #e74c3c;
  color: white;
}

.hal-link:hover {
  background: #c0392b;
  color: white;
}

.status-badge {
  display: inline-block;
  padding: 3px 8px;
  border-radius: 12px;
  font-size: 0.8em;
  font-weight: bold;
  margin-left: 10px;
}

.published {
  background: #d5f4e6;
  color: #27ae60;
}

.under-review {
  background: #fff3cd;
  color: #856404;
}

.thesis {
  background: #e8f4f8;
  color: #17a2b8;
}

.conference-item {
  background: #f0f8ff;
  border-left: 4px solid #27ae60;
  padding: 15px;
  margin: 12px 0;
  border-radius: 0 6px 6px 0;
}

.conference-title {
  font-weight: bold;
  color: #2c3e50;
  margin-bottom: 5px;
}

.conference-details {
  color: #7f8c8d;
  font-size: 0.95em;
}

.external-links {
  background: #f8f9fa;
  padding: 20px;
  border-radius: 8px;
  margin: 30px 0;
  text-align: center;
}

.external-links a {
  display: inline-block;
  background: #6c757d;
  color: white;
  padding: 10px 20px;
  margin: 5px;
  border-radius: 25px;
  text-decoration: none;
  transition: background 0.3s ease;
}

.external-links a:hover {
  background: #495057;
  color: white;
}

.award-item {
  background: #fff8e1;
  border-left: 4px solid #ff9800;
  padding: 15px;
  margin: 12px 0;
  border-radius: 0 6px 6px 0;
}
</style>

<div class="research-focus">
  <h2>🔬 My Research Focus</h2>
  <p>My research focuses on <strong>clustering longitudinal mixed-type data</strong> for modeling longitudinal surveys. I develop statistical methods that can handle the complexity of real-world data that evolves over time and contains different types of variables (continuous, ordinal, categorical). My work has applications in healthcare, social sciences, and survey research, particularly in understanding behavioral patterns and policy impacts over time.</p>
  
  <p>I completed my PhD in Applied Mathematics at Université Lyon 2 under the supervision of <strong>Julien Jacques</strong> and <strong>Isabelle Prim-Allaz</strong>, with my thesis defended in May 2025.</p>
</div>

<div class="research-interests">
  <div class="interest-card">
    <h4>🔍 Statistical Clustering</h4>
    <p>Finite mixture models for complex data structures</p>
  </div>
  <div class="interest-card">
    <h4>📊 Longitudinal Data</h4>
    <p>Time series analysis and temporal pattern recognition</p>
  </div>
  <div class="interest-card">
    <h4>🔀 Mixed-Type Data</h4>
    <p>Methods for heterogeneous data types</p>
  </div>
</div>

<div class="external-links">
  {% if site.author.googlescholar %}
    <a href="{{site.author.googlescholar}}" target="_blank">📚 Google Scholar</a>
  {% endif %}
  <a href="https://cv.hal.science/francesco-amato" target="_blank">🔬 HAL Profile</a>
  <a href="https://orcid.org/0000-0002-1234-5678" target="_blank">🆔 ORCID</a>
</div>

## 📖 Publications

### Journal Articles

<div class="pub-item">
  <div class="pub-title">Clustering longitudinal ordinal data via finite mixture of matrix-variate distributions</div>
  <div class="pub-authors"><strong>Francesco Amato</strong>, Julien Jacques, Isabelle Prim-Allaz</div>
  <div class="pub-venue">Statistics and Computing, vol. 34, article 81 (2024)</div>
  <div class="pub-links">
    <a href="https://doi.org/10.1007/s11222-024-10390-z" class="doi-link" target="_blank">DOI</a>
    <a href="https://hal.science/hal-04105669v2" class="hal-link" target="_blank">HAL</a>
    <span class="status-badge published">Published</span>
  </div>
</div>

<div class="pub-item">
  <div class="pub-title">A Comparison of Migrant Integration Policies via Mixture of Matrix-Normals</div>
  <div class="pub-authors">Salvatore Leonardo Alaimo, <strong>Francesco Amato</strong>, Filomena Maggino, Alfonso Piscitelli, Emiliano Seri</div>
  <div class="pub-venue">Social Indicators Research, vol. 165, pp. 473–494 (2023)</div>
  <div class="pub-links">
    <a href="https://doi.org/10.1007/s11205-022-03024-2" class="doi-link" target="_blank">DOI</a>
    <a href="https://hal.science/hal-04025722v1" class="hal-link" target="_blank">HAL</a>
    <span class="status-badge published">Published</span>
  </div>
</div>

### Under Review

<div class="pub-item">
  <div class="pub-title">MMM: Clustering Multivariate Longitudinal Mixed-type Data</div>
  <div class="pub-authors"><strong>Francesco Amato</strong>, Julien Jacques</div>
  <div class="pub-venue">Submitted to Journal of Computational and Graphical Statistics (2024)</div>
  <div class="pub-links">
    <a href="https://hal.science/hal-04807626v1" class="hal-link" target="_blank">HAL Preprint</a>
    <span class="status-badge under-review">Under Review</span>
  </div>
</div>

### PhD Thesis

<div class="pub-item">
  <div class="pub-title">Mixed data temporal clustering for modelling longitudinal surveys</div>
  <div class="pub-authors"><strong>Francesco Amato</strong></div>
  <div class="pub-venue">PhD Thesis, Université Lumière Lyon 2 (Expected May 2025)</div>
  <div style="margin-top: 8px; font-size: 0.9em; color: #666;">
    Supervisors: Julien Jacques, Isabelle Prim-Allaz<br>
    Laboratory: ERIC (Entrepôts, Représentation et Ingénierie des Connaissances)
  </div>
  <span class="status-badge thesis">In Progress</span>
</div>

## 🔬 Research Projects in Progress

<div class="pub-item">
  <div class="pub-title">Model-based Clustering for Longitudinal Mixed-type Data: a Survey</div>
  <div class="pub-venue">Ongoing Drafting</div>
  <div style="margin-top: 8px; font-size: 0.9em; color: #666;">
    Literature survey on clustering methods for longitudinal, mixed-type and longitudinal mixed-type data, based on Chapter 3 (state of the art) of my PhD thesis.
  </div>
</div>

<div class="pub-item">
  <div class="pub-title">ClustMMM</div>
  <div class="pub-venue">Ongoing Implementation</div>
  <div style="margin-top: 8px; font-size: 0.9em; color: #666;">
    R package implementing the MMM algorithm for clustering multivariate longitudinal mixed-type data. It will include comprehensive documentation, examples, and validation datasets.
  </div>
</div>

## 🎯 Research Focus

<div class="pub-item">
  <div class="pub-title">🔧 Statistical Methodology</div>
  <div style="margin-top: 8px; font-size: 0.9em; color: #666;">
    Development of finite mixture models specifically designed for longitudinal data with mixed variable types (continuous, ordinal, categorical). Focus on matrix-variate distributions and latent variable approaches.
  </div>
</div>

<div class="pub-item">
  <div class="pub-title">📐 Mathematical Framework</div>
  <div style="margin-top: 8px; font-size: 0.9em; color: #666;">
    Advanced probability theory, optimization algorithms (EM algorithm variations), and matrix calculus for handling complex data structures that evolve over time.
  </div>
</div>

<div class="pub-item">
  <div class="pub-title">💡 Applied Research</div>
  <div style="margin-top: 8px; font-size: 0.9em; color: #666;">
    Real-world applications in longitudinal surveys, social policy analysis, and financial data clustering with focus on practical implementation and interpretation.
  </div>
</div>


## 💻 Software & Code

<div class="pub-item">
  <div class="pub-title">Research Code Repository</div>
  <div style="margin-top: 8px; font-size: 0.9em; color: #666;">
    Reproducible code for published research papers with README files, sample datasets, and step-by-step analysis scripts. Some open, some available on request for collaboration purposes.
  </div>
</div>

{% comment %}
<!-- Keep the original Jekyll publication loop in case you want to use it later -->
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
  {% if post.authors %}<div class="pub-authors">{{ post.authors }}</div>{% endif %}
  <div class="pub-venue">{{ post.venue }}, {{ post.date | date: "%Y" }}</div>
</div>
    {% endif %}
  {% endfor %}
{% endfor %}
{% endcomment %}
