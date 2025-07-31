---
layout: archive
title: "Talks and presentations"
permalink: /talks/
author_profile: true
---

<style>
.talks-intro {
  background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
  color: white;
  padding: 25px;
  border-radius: 8px;
  margin: 30px 0;
}

.talks-intro h2 {
  color: white;
  margin-top: 0;
  border-bottom: 2px solid rgba(255,255,255,0.3);
  padding-bottom: 10px;
}

.talk-category {
  margin: 40px 0;
}

.talk-category h3 {
  color: #2c3e50;
  border-left: 4px solid #3498db;
  padding-left: 15px;
  margin-bottom: 20px;
}

.invited-talk {
  background: #f8f9ff;
  border-left: 4px solid #e74c3c;
  padding: 20px;
  margin: 15px 0;
  border-radius: 0 8px 8px 0;
  transition: transform 0.2s ease;
}

.contributed-talk {
  background: #f0f8ff;
  border-left: 4px solid #3498db;
  padding: 20px;
  margin: 15px 0;
  border-radius: 0 8px 8px 0;
  transition: transform 0.2s ease;
}

.poster-talk {
  background: #f5f5f5;
  border-left: 4px solid #27ae60;
  padding: 20px;
  margin: 15px 0;
  border-radius: 0 8px 8px 0;
  transition: transform 0.2s ease;
}

.talk-item:hover {
  transform: translateX(5px);
}

.talk-title {
  font-weight: bold;
  color: #2c3e50;
  font-size: 1.1em;
  margin-bottom: 8px;
}

.talk-venue {
  color: #34495e;
  margin-bottom: 5px;
  font-size: 1em;
}

.talk-location {
  color: #7f8c8d;
  font-style: italic;
  margin-bottom: 5px;
}

.talk-date {
  color: #95a5a6;
  font-size: 0.9em;
  margin-bottom: 10px;
}

.talk-type-badge {
  display: inline-block;
  padding: 3px 10px;
  border-radius: 12px;
  font-size: 0.8em;
  font-weight: bold;
  margin-top: 8px;
}

.invited-badge {
  background: #ffebee;
  color: #c62828;
}

.contributed-badge {
  background: #e3f2fd;
  color: #1565c0;
}

.poster-badge {
  background: #e8f5e8;
  color: #2e7d32;
}

.talk-abstract {
  margin-top: 10px;
  font-size: 0.95em;
  color: #555;
  font-style: italic;
}

.stats-section {
  background: #f8f9fa;
  padding: 20px;
  border-radius: 8px;
  margin: 30px 0;
  text-align: center;
}

.stats-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(150px, 1fr));
  gap: 20px;
  margin-top: 20px;
}

.stat-card {
  background: white;
  padding: 15px;
  border-radius: 8px;
  box-shadow: 0 2px 4px rgba(0,0,0,0.1);
}

.stat-number {
  font-size: 2em;
  font-weight: bold;
  color: #3498db;
}

.stat-label {
  color: #7f8c8d;
  font-size: 0.9em;
  margin-top: 5px;
}

.conference-links {
  margin-top: 8px;
}

.conference-links a {
  display: inline-block;
  background: #6c757d;
  color: white;
  padding: 3px 8px;
  border-radius: 4px;
  text-decoration: none;
  font-size: 0.8em;
  margin-right: 5px;
}

.conference-links a:hover {
  background: #495057;
  color: white;
}
</style>

<div class="talks-intro">
  <h2>🎤 Presentations Overview</h2>
  <p>My research has been presented at leading international conferences in statistics, computational statistics, and data science. I have been invited to speak at several prestigious venues and have contributed to major statistical conferences across Europe and beyond. My presentations focus on clustering methods for longitudinal mixed-type data and their applications in social sciences and healthcare.</p>
</div>

{% if site.talkmap_link == true %}
<p style="text-decoration:underline;"><a href="/talkmap.html">🗺️ See a map of all the places I've given a talk!</a></p>
{% endif %}

<div class="stats-section">
  <h3>📊 Presentation Statistics</h3>
  <div class="stats-grid">
    <div class="stat-card">
      <div class="stat-number">3</div>
      <div class="stat-label">Invited Talks</div>
    </div>
    <div class="stat-card">
      <div class="stat-number">4</div>
      <div class="stat-label">Contributed Talks</div>
    </div>
    <div class="stat-card">
      <div class="stat-number">3</div>
      <div class="stat-label">Poster Presentations</div>
    </div>
    <div class="stat-card">
      <div class="stat-number">7</div>
      <div class="stat-label">Countries</div>
    </div>
  </div>
</div>

<div class="talk-category">
  <h3>🎯 Invited Talks</h3>
  
  <div class="invited-talk talk-item">
    <div class="talk-title">Clustering Longitudinal Mixed-type Data</div>
    <div class="talk-venue">18th International Joint Conference CFE-CMStatistics (CFE-CMStatistics)</div>
    <div class="talk-location">📍 London, United Kingdom</div>
    <div class="talk-date">🗓️ December 11-13, 2024</div>
    <div class="talk-abstract">
      Presentation of the MMM algorithm for clustering multivariate longitudinal mixed-type data, with applications to healthcare and social survey analysis. Focus on methodological innovations and practical implementation.
    </div>
    <span class="talk-type-badge invited-badge">Invited Speaker</span>
  </div>

  <div class="invited-talk talk-item">
    <div class="talk-title">Clustering de données longitudinales mixtes</div>
    <div class="talk-venue">Rencontres Statistiques Lyonnaises</div>
    <div class="talk-location">📍 Lyon, France</div>
    <div class="talk-date">🗓️ July 12, 2024</div>
    <div class="talk-abstract">
      Local presentation of research progress on mixed-type longitudinal clustering methods, delivered in French to the Lyon statistical community.
    </div>
    <span class="talk-type-badge invited-badge">Invited Speaker</span>
  </div>

  <div class="invited-talk talk-item">
    <div class="talk-title">Clustering Longitudinal Ordinal Data</div>
    <div class="talk-venue">29th Nordic Conference in Mathematical Statistics (NORDSTAT)</div>
    <div class="talk-location">📍 Gothenburg, Sweden</div>
    <div class="talk-date">🗓️ June 19-22, 2023</div>
    <div class="talk-abstract">
      Presentation of finite mixture models for matrix-variate distributions applied to longitudinal ordinal data, with theoretical foundations and empirical validation.
    </div>
    <span class="talk-type-badge invited-badge">Invited Speaker</span>
  </div>
</div>

<div class="talk-category">
  <h3>📢 Contributed Talks</h3>
  
  <div class="contributed-talk talk-item">
    <div class="talk-title">Clustering Longitudinal Mixed Data</div>
    <div class="talk-venue">International Conference on Statistics and Data Science (ICSDS), IMS</div>
    <div class="talk-location">📍 Nice, France</div>
    <div class="talk-date">🗓️ December 16-19, 2024</div>
    <div class="talk-abstract">
      Latest developments in the MMM methodology with focus on computational efficiency and scalability for large-scale longitudinal studies.
    </div>
    <span class="talk-type-badge contributed-badge">Contributed Talk</span>
  </div>

  <div class="contributed-talk talk-item">
    <div class="talk-title">Clustering Longitudinal Mixed Data</div>
    <div class="talk-venue">55èmes Journées de la Statistique (JdS)</div>
    <div class="talk-location">📍 Bordeaux, France</div>
    <div class="talk-date">🗓️ May 27-31, 2024</div>
    <div class="talk-abstract">
      Presentation of mixed-type clustering advances at France's premier statistics conference, emphasizing practical applications and software implementation.
    </div>
    <span class="talk-type-badge contributed-badge">Contributed Talk</span>
  </div>

  <div class="contributed-talk talk-item">
    <div class="talk-title">Clustering Longitudinal Ordinal Data</div>
    <div class="talk-venue">24th International Conference on Computational Statistics (COMPSTAT)</div>
    <div class="talk-location">📍 Bologna, Italy</div>
    <div class="talk-date">🗓️ August 23-26, 2022</div>
    <div class="talk-abstract">
      Early presentation of ordinal data clustering methodology at the leading computational statistics conference, focusing on algorithmic innovations.
    </div>
    <span class="talk-type-badge contributed-badge">Contributed Talk</span>
  </div>

  <div class="contributed-talk talk-item">
    <div class="talk-title">Clustering Longitudinal Ordinal Data via Finite Mixture of Matrix-Variate Latent Gaussians</div>
    <div class="talk-venue">53èmes Journées de la Statistique (JdS)</div>
    <div class="talk-location">📍 Lyon, France</div>
    <div class="talk-date">🗓️ June 13-17, 2022</div>
    <div class="talk-abstract">
      Introduction of the matrix-variate latent Gaussian approach for longitudinal ordinal clustering, with theoretical justification and simulation studies.
    </div>
    <span class="talk-type-badge contributed-badge">Contributed Talk</span>
  </div>
</div>

<div class="talk-category">
  <h3>📋 Poster Presentations</h3>
  
  <div class="poster-talk talk-item">
    <div class="talk-title">Clustering Longitudinal Mixed Data</div>
    <div class="talk-venue">Working Group on Model-Based Clustering, summer session 2024</div>
    <div class="talk-location">📍 Bertinoro, Italy</div>
    <div class="talk-date">🗓️ July 22-26, 2024</div>
    <div class="talk-abstract">
      Interactive poster session presenting the MMM algorithm to the international model-based clustering community, fostering collaborative discussions and feedback.
    </div>
    <div class="conference-links">
      <a href="https://hal.science/hal-04849830v1" target="_blank">HAL Document</a>
    </div>
    <span class="talk-type-badge poster-badge">Poster</span>
  </div>

  <div class="poster-talk talk-item">
    <div class="talk-title">Clustering Longitudinal Ordinal Data</div>
    <div class="talk-venue">Working Group on Model-Based Clustering, summer session 2023</div>
    <div class="talk-location">📍 Pittsburgh, United States</div>
    <div class="talk-date">🗓️ July 17-21, 2023</div>
    <div class="talk-abstract">
      International poster presentation showcasing ordinal data clustering methods to leading researchers in model-based clustering from around the world.
    </div>
    <div class="conference-links">
      <a href="https://hal.science/hal-04849855v1" target="_blank">HAL Document</a>
    </div>
    <span class="talk-type-badge poster-badge">Poster</span>
  </div>

  <div class="poster-talk talk-item">
    <div class="talk-title">Clustering Longitudinal Ordinal Data</div>
    <div class="talk-venue">StatLearn</div>
    <div class="talk-location">📍 Cargèse, France</div>
    <div class="talk-date">🗓️ April 4-7, 2022</div>
    <div class="talk-abstract">
      Early-stage research presentation at the statistical learning conference, receiving valuable feedback from the machine learning and statistics community.
    </div>
    <div class="conference-links">
      <a href="https://hal.univ-lyon2.fr/hal-03657085v1" target="_blank">HAL Document</a>
    </div>
    <span class="talk-type-badge poster-badge">Poster</span>
  </div>
</div>

<div class="talk-category">
  <h3>🌍 Geographic Distribution</h3>
  
  <div class="stats-section">
    <p>My presentations have taken me across Europe and North America, building an international network of collaborators and establishing my research visibility in the global statistical community.</p>
    
    <div class="stats-grid">
      <div class="stat-card">
        <div style="font-size: 1.2em; margin-bottom: 10px;">🇫🇷 France</div>
        <div class="stat-label">4 presentations</div>
      </div>
      <div class="stat-card">
        <div style="font-size: 1.2em; margin-bottom: 10px;">🇮🇹 Italy</div>
        <div class="stat-label">2 presentations</div>
      </div>
      <div class="stat-card">
        <div style="font-size: 1.2em; margin-bottom: 10px;">🇬🇧 UK</div>
        <div class="stat-label">1 presentation</div>
      </div>
      <div class="stat-card">
        <div style="font-size: 1.2em; margin-bottom: 10px;">🇸🇪 Sweden</div>
        <div class="stat-label">1 presentation</div>
      </div>
      <div class="stat-card">
        <div style="font-size: 1.2em; margin-bottom: 10px;">🇺🇸 USA</div>
        <div class="stat-label">1 presentation</div>
      </div>
    </div>
  </div>
</div>

<div class="talk-category">
  <h3>🔗 Additional Presentations</h3>
  
  <div class="contributed-talk talk-item">
    <div class="talk-title">A longitudinal cross country comparison of migrant integration policies via Mixture of Matrix-Normals</div>
    <div class="talk-venue">SIS 2022 - The 51st Scientific Meeting of the Italian Statistical Society</div>
    <div class="talk-location">📍 Caserta, Italy</div>
    <div class="talk-date">🗓️ June 2022</div>
    <div class="talk-abstract">
      Collaborative presentation with Salvatore Leonardo Alaimo and Emiliano Seri on migration policy analysis using advanced statistical methods.
    </div>
    <div class="conference-links">
      <a href="https://hal.univ-lyon2.fr/hal-03661665v1" target="_blank">HAL Document</a>
    </div>
    <span class="talk-type-badge contributed-badge">Contributed Talk</span>
  </div>
</div>

{% comment %}
<!-- Keep the original Jekyll talk loop in case you want to use it later -->
{% for post in site.talks reversed %}
  {% include archive-single-talk.html %}
{% endfor %}
{% endcomment %}
