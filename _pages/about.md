---
layout: single
title: ""
permalink: /
author_profile: true
classes: wide
---

<div class="hero-section" markdown="1">
# Hey, I'm Yichuan Liu
{: .text-center}

I'm a Business Analytics student at NUS, passionate about data science, AI, and creative arts. Here you can explore my projects, artwork, and thoughts.
{: .text-center .intro-text}
</div>

<div class="featured-work" markdown="1">
## Featured Work
{: .section-title}

<div class="project-grid" markdown="1">
<div class="project-card" markdown="1">
### [TradeGuardian AI](https://github.com/bnb-hack)
AI-powered DeFi trading assistant with natural language interface
</div>

<div class="project-card" markdown="1">
### [NUSGlance](https://bt3103-7c86e.web.app)
Unified academic tracking platform for better student experience
</div>

<div class="project-card" markdown="1">
### [Social Influence Analysis](projects/social-influence)
Graph Neural Networks for political influence analysis
</div>
</div>
</div>

<style>
.hero-section {
  padding: 4em 0;
  background: linear-gradient(to right, #f8f9fa, #e9ecef);
  border-radius: 10px;
  margin-bottom: 3em;
}

.text-center {
  text-align: center;
}

.intro-text {
  font-size: 1.2em;
  color: #495057;
  max-width: 600px;
  margin: 1em auto;
  line-height: 1.6;
}

.section-title {
  color: #2c3e50;
  border-bottom: 2px solid #3498db;
  padding-bottom: 0.3em;
  margin-bottom: 1.5em;
}

.project-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
  gap: 2em;
  margin-top: 2em;
}

.project-card {
  background: white;
  padding: 1.5em;
  border-radius: 10px;
  box-shadow: 0 4px 6px rgba(0,0,0,0.1);
  transition: transform 0.2s ease, box-shadow 0.2s ease;
}

.project-card:hover {
  transform: translateY(-5px);
  box-shadow: 0 6px 12px rgba(0,0,0,0.15);
}

.project-card h3 {
  margin-top: 0;
  color: #2c3e50;
}

.project-card a {
  color: #3498db;
  text-decoration: none;
}

.project-card a:hover {
  text-decoration: underline;
}

@media (max-width: 768px) {
  .hero-section {
    padding: 2em 1em;
  }
  
  .project-grid {
    grid-template-columns: 1fr;
  }
}
</style>