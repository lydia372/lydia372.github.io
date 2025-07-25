---
layout: single
title: "Projects"
permalink: /projects/
author_profile: true
classes: wide
---

<style>
.page__content {
  padding-right: 200px;
}

.projects-container {
  display: grid;
  grid-template-columns: repeat(2, minmax(0, 1fr));
  gap: 1.5em;
  margin: 2em 0;
  max-width: 100%;
}

.project-card {
  background: white;
  border-radius: 12px;
  overflow: hidden;
  transition: transform 0.2s ease;
  text-decoration: none;
  color: inherit;
  border: 1px solid #edf2f7;
  width: 100%;
  display: flex;
  flex-direction: column;
}

.project-card:hover {
  transform: translateY(-2px);
  box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
}

.project-image-wrapper {
  width: 100%;
  height: 200px;
  overflow: hidden;
}

.project-image {
  width: 100%;
  height: 100%;
  object-fit: cover;
  display: block;
}

.project-content {
  padding: 1.5em;
  flex: 1;
  display: flex;
  flex-direction: column;
}

.project-title {
  font-size: 1.3em;
  color: #2d3748;
  margin: 0 0 0.8em 0;
  font-weight: 600;
}

.project-description {
  color: #4a5568;
  font-size: 0.95em;
  line-height: 1.6;
  margin-bottom: 1.2em;
  flex: 1;
}

.skills-list {
  display: flex;
  flex-wrap: wrap;
  gap: 0.5em;
  margin-bottom: 1.2em;
}

.skill-tag {
  background: #ebf5ff;
  color: #4299e1;
  padding: 0.3em 0.8em;
  border-radius: 15px;
  font-size: 0.85em;
  font-weight: 500;
}

.read-more {
  color: #4299e1;
  text-decoration: none;
  font-size: 0.95em;
  font-weight: 500;
  display: inline-flex;
  align-items: center;
  margin-top: auto;
}

.read-more::after {
  content: "→";
  margin-left: 0.3em;
  transition: transform 0.2s ease;
}

.read-more:hover::after {
  transform: translateX(3px);
}

@media (max-width: 1200px) {
  .projects-container {
    grid-template-columns: 1fr;
  }
  
  .project-image-wrapper {
    height: 180px;
  }
  
  .project-content {
    padding: 1.2em;
  }

  .page__content {
    padding-right: 0;
  }
}

@media (min-width: 80em) {
  .page__content {
    padding-right: 300px;
  }
}
</style>

<div class="projects-container">

<div class="project-card">
<div class="project-image-wrapper">
![TradeGuardian AI](/images/tradeguardian.jpg){: .project-image}
</div>
<div class="project-content">
<h2 class="project-title">TradeGuardian AI</h2>
<div class="project-description">
Developed an AI-powered DeFi trading assistant that enables users to execute crypto trades via natural language through a chatbot interface. Integrated OpenAI for adaptive decision-making, Jupiter Aggregator for pre-trade simulation and on-chain execution.
</div>
<div class="skills-list">
<span class="skill-tag">Python</span>
<span class="skill-tag">OpenAI</span>
<span class="skill-tag">Blockchain</span>
</div>
[Read more](https://github.com/bnb-hack){: .read-more}
</div>
</div>

<div class="project-card">
<div class="project-image-wrapper">
![NUSGlance](/images/nusglance.jpg){: .project-image}
</div>
<div class="project-content">
<h2 class="project-title">NUSGlance Academic Tracker</h2>
<div class="project-description">
Designed and developed a unified academic tracking platform using Vue.js and Firebase to consolidate disparate learning tools into a seamless, centralized dashboard. This streamlined approach improved students' visibility over coursework.
</div>
<div class="skills-list">
<span class="skill-tag">Vue.js</span>
<span class="skill-tag">Firebase</span>
<span class="skill-tag">JavaScript</span>
</div>
[Read more](https://bt3103-7c86e.web.app){: .read-more}
</div>
</div>

<div class="project-card">
<div class="project-image-wrapper">
![Social Influence](/images/social-influence.jpg){: .project-image}
</div>
<div class="project-content">
<h2 class="project-title">Social Influence Analysis</h2>
<div class="project-description">
Developed a simulation of voter behavior on a social graph to evaluate political influence strategies. Built an undirected graph from shared hobbies and modeled daily vote propagation until stabilization using spectral graph theory.
</div>
<div class="skills-list">
<span class="skill-tag">Python</span>
<span class="skill-tag">Graph Neural Networks</span>
<span class="skill-tag">NetworkX</span>
</div>
[Read more](https://github.com/lydia372/Social-Influence-Optimization-via-Graph-Neural-Networks/tree/main){: .read-more}
</div>
</div>

</div>