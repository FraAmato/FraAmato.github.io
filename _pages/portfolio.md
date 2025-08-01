---
layout: archive
title: "Portfolio"
permalink: /portfolio/
author_profile: true
---

<style>
.portfolio-intro {
  background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
  color: white;
  padding: 25px;
  border-radius: 8px;
  margin: 30px 0;
  text-align: center;
}

.portfolio-intro h2 {
  color: white;
  margin-top: 0;
  border-bottom: 2px solid rgba(255,255,255,0.3);
  padding-bottom: 10px;
}

.coming-soon-card {
  background: #f8f9ff;
  border-left: 4px solid #3498db;
  padding: 30px;
  margin: 30px 0;
  border-radius: 0 8px 8px 0;
  text-align: center;
  transition: transform 0.2s ease;
}

.coming-soon-card:hover {
  transform: translateX(5px);
}

.big-emoji {
  font-size: 4em;
  margin: 20px 0;
  animation: bounce 2s infinite;
}

@keyframes bounce {
  0%, 20%, 50%, 80%, 100% {
    transform: translateY(0);
  }
  40% {
    transform: translateY(-10px);
  }
  60% {
    transform: translateY(-5px);
  }
}

.future-plans {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
  gap: 20px;
  margin: 30px 0;
}

.plan-card {
  background: linear-gradient(135deg, #74b9ff, #0984e3);
  color: white;
  padding: 25px;
  border-radius: 8px;
  text-align: center;
  transition: transform 0.2s ease;
  opacity: 0.8;
}

.plan-card:hover {
  transform: translateY(-5px);
  opacity: 1;
}

.plan-card h4 {
  margin-top: 0;
  margin-bottom: 15px;
  font-size: 1.1em;
}

.plan-card .emoji {
  font-size: 2em;
  margin-bottom: 10px;
  display: block;
}

.teaser-section {
  background: #fff8e1;
  border-left: 4px solid #ff9800;
  padding: 25px;
  margin: 30px 0;
  border-radius: 0 8px 8px 0;
}

.teaser-section h3 {
  color: #e65100;
  margin-top: 0;
}

.progress-bar {
  background: #e0e0e0;
  border-radius: 25px;
  padding: 3px;
  margin: 20px 0;
}

.progress-fill {
  background: linear-gradient(90deg, #3498db, #2ecc71);
  height: 20px;
  border-radius: 22px;
  width: 15%;
  transition: width 0.3s ease;
  position: relative;
  overflow: hidden;
}

.progress-fill::after {
  content: '';
  position: absolute;
  top: 0;
  left: 0;
  bottom: 0;
  right: 0;
  background: linear-gradient(90deg, transparent, rgba(255,255,255,0.3), transparent);
  animation: shimmer 2s infinite;
}

@keyframes shimmer {
  0% {
    transform: translateX(-100%);
  }
  100% {
    transform: translateX(100%);
  }
}

.stay-tuned {
  background: #f0f8ff;
  border: 2px dashed #3498db;
  padding: 25px;
  margin: 30px 0;
  border-radius: 8px;
  text-align: center;
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

.fun-fact {
  background: #e8f5e8;
  border-left: 4px solid #27ae60;
  padding: 20px;
  margin: 25px 0;
  border-radius: 0 8px 8px 0;
  text-align: center;
}

.rotating-text {
  display: inline-block;
  animation: rotate 4s linear infinite;
}

@keyframes rotate {
  from {
    transform: rotate(0deg);
  }
  to {
    transform: rotate(360deg);
  }
}
</style>

<div class="portfolio-intro">
  <h2>🎨 Portfolio</h2>
  <p>Welcome to my portfolio page! While this space is currently taking a well-deserved coffee break ☕, exciting projects are brewing behind the scenes.</p>
</div>

<div class="coming-soon-card">
  <div class="big-emoji">🚧</div>
  <h2 style="color: #2c3e50; margin-bottom: 15px;">Under Construction</h2>
  <p style="font-size: 1.1em; color: #555; margin-bottom: 10px;">
    There's nothing here for now, but I hope to fill it soon! <span style="font-size: 1.2em;">😉</span>
  </p>
  <p style="color: #7f8c8d; font-style: italic;">
    Great things take time, and this portfolio will be worth the wait!
  </p>
</div>

<div class="teaser-section">
  <h3>🔮 What's Coming?</h3>
  <p>This space will soon showcase my journey from statistical theory to practical applications. Think of it as the exciting sequel to my research, talks, and teaching pages!</p>
  
  <div style="margin: 20px 0;">
    <strong>Portfolio Progress:</strong>
    <div class="progress-bar">
      <div class="progress-fill"></div>
    </div>
    <small style="color: #666;">15% complete - Ideas brewing! ☕</small>
  </div>
</div>

<div class="future-plans">
  <div class="plan-card">
    <span class="emoji">📊</span>
    <h4>Data Visualizations</h4>
    <p>Interactive charts and graphs showcasing my statistical analyses and research findings.</p>
  </div>
  
  <div class="plan-card">
    <span class="emoji">💻</span>
    <h4>Code Projects</h4>
    <p>R packages, Python tools, and statistical applications I've developed during my research.</p>
  </div>
  
  <div class="plan-card">
    <span class="emoji">🎓</span>
    <h4>Educational Content</h4>
    <p>Teaching materials, tutorials, and resources I've created for statistics and data science.</p>
  </div>
  
  <div class="plan-card">
    <span class="emoji">🔬</span>
    <h4>Research Demos</h4>
    <p>Interactive demonstrations of my clustering algorithms and statistical methods.</p>
  </div>
</div>

<div class="fun-fact">
  <h3 style="margin-top: 0;">🎯 Fun Fact</h3>
  <p>Did you know that empty portfolios have a 100% potential for improvement? <span class="rotating-text">📈</span></p>
  <p style="margin-bottom: 0; color: #666; font-size: 0.9em;">
    (That's some solid statistical reasoning right there!)
  </p>
</div>

<div class="stay-tuned">
  <h3 style="color: #3498db; margin-top: 0;">📡 Stay Tuned!</h3>
  <p style="margin-bottom: 15px;">
    While you're waiting for this portfolio to come to life, feel free to explore my other pages:
  </p>
  
  <div class="external-links">
    <a href="/research/">📚 Check out my Research</a>
    <a href="/talks/">🎤 Browse my Presentations</a>
    <a href="/teaching/">👨‍🏫 Explore my Teaching</a>
    <a href="/cv/">📄 View my CV</a>
  </div>
  
  <p style="color: #666; font-style: italic; margin-top: 15px;">
    Or come back later and be surprised by what shows up here! <span style="font-size: 1.2em;">✨</span>
  </p>
</div>

<div class="coming-soon-card" style="background: linear-gradient(135deg, #ffeaa7, #fdcb6e); border-left: 4px solid #e17055;">
  <h3 style="color: #2d3436; margin-top: 0;">💡 Have Ideas?</h3>
  <p style="color: #2d3436;">
    If you have suggestions for what you'd like to see in this portfolio, 
    I'm always open to feedback and collaboration ideas!
  </p>
  <div style="margin-top: 15px;">
    <a href="mailto:francesco.amato@univ-lyon2.fr" style="color: #2d3436; text-decoration: none; font-weight: bold;">
      📧 Drop me a line!
    </a>
  </div>
</div>
