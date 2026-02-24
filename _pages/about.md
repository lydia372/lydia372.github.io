---
layout: single
title: ""
permalink: /
author_profile: true
classes: wide
---

<style>
.page__content {
  padding-right: 0;
}

@media (min-width: 80em) {
  .page__content {
    margin-right: 300px;
  }
}

.author__avatar {
  display: block;
  width: 100%;
  max-width: 200px;
  margin: 0 auto 1em;
}

.author__avatar img {
  max-width: 200px;
  border-radius: 50%;
  border: 3px solid #fff;
  box-shadow: 0 0 10px rgba(0,0,0,0.1);
}

.sidebar.sticky {
  opacity: 1 !important;
  -webkit-transition: opacity 0.75s ease-in-out;
  transition: opacity 0.75s ease-in-out;
}

@media (min-width: 64em) {
  .author__avatar {
    display: block;
    width: auto;
    max-width: 250px;
    margin: 0 auto 1em;
  }

  .author__avatar img {
    max-width: 250px;
    padding: 5px;
  }
}
</style>

<div class="hero-section" markdown="1">
## Hi, I'm Yichuan Liu
{: .hero-title}

<div class="hero-subtitle" markdown="1">
Business Analytics @ NUS | AI x Finance
</div>

<div class="hero-description" markdown="1">
I build AI-driven tools for trading, decision support, and student success. \\
Currently interning at Monee (Insurance & Fintech) in Singapore.
</div>
</div>

<div class="bio-section" markdown="1">
## Bio
{: .section-title}

I'm a Business Analytics student at NUS focused on machine learning, behavioral modeling, and data products. I've built autonomous trading agents, social influence simulations, and academic platforms that help students manage coursework more efficiently. I'm most interested in AI for finance and human decision-making.
</div>

<div class="highlights" markdown="1">
## Highlights
{: .section-title}

- Built AI trading agents that combine market signals with natural language interfaces.
- Modeled social influence dynamics with graph neural networks and simulation.
- Shipped student tools like NUSGlance to improve academic planning and visibility.
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
### [Social Influence Analysis](https://github.com/lydia372/Social-Influence-Optimization-via-Graph-Neural-Networks/tree/main)
Graph Neural Networks for political influence analysis
</div>
</div>
</div>

<style>
.hero-section {
  padding: 3em 2em;
  background: linear-gradient(135deg, #f8f9fa 0%, #e9ecef 100%);
  border-radius: 15px;
  margin-bottom: 3em;
  text-align: center;
  position: relative;
  overflow: hidden;
  width: 100%;
}

.hero-section::before {
  content: '';
  position: absolute;
  top: 0;
  left: 0;
  right: 0;
  bottom: 0;
  background: linear-gradient(45deg, rgba(52, 152, 219, 0.05) 0%, rgba(52, 152, 219, 0) 100%);
  z-index: 1;
}

.hero-title {
  font-size: 3.5em;
  font-size: 2.8em;
  font-weight: 700;
  color: #2c3e50;
  margin-bottom: 0.3em;
  letter-spacing: -0.02em;
  line-height: 1.2;
  position: relative;
  z-index: 2;
}

.hero-subtitle {
  font-size: 1.5em;
  font-size: 1.3em;
  color: #3498db;
  margin-bottom: 1.5em;
  margin-bottom: 1.2em;
  font-weight: 500;
  position: relative;
  z-index: 2;
}

.hero-description {
  font-size: 1.2em;
  font-size: 1.1em;
  color: #495057;
  max-width: 600px;
  max-width: 500px;
  margin: 0 auto;
  line-height: 1.8;
  line-height: 1.6;
  position: relative;
  z-index: 2;
}

.text-center {
  text-align: center;
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
    margin-left: 0;
    margin-right: 0;
    width: 100%;
  }

  .page__content {
    margin-right: 0;
  }

  .hero-title {
    font-size: 2.5em;
    font-size: 2em;
  }

  .hero-subtitle {
    font-size: 1.2em;
    font-size: 1.1em;
  }

  .hero-description {
    font-size: 1em;
    max-width: 100%;
  }

  .project-grid {
    grid-template-columns: 1fr;
  }
}
</style>
