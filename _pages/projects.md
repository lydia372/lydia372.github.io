---
layout: single
title: "Projects"
permalink: /projects/
author_profile: true
classes: wide
---

<style>
.projects-container {
  max-width: 900px;
  margin: 2em auto;
}

.project-card {
  background: white;
  border-radius: 8px;
  margin-bottom: 2em;
  overflow: hidden;
  transition: transform 0.2s ease;
  display: block;
  text-decoration: none;
  color: inherit;
}

.project-card:hover {
  transform: translateY(-2px);
}

.project-image {
  width: 100%;
  height: 300px;
  object-fit: cover;
}

.project-content {
  padding: 1.5em;
}

.project-title {
  font-size: 1.6em;
  color: #2c3e50;
  margin: 0 0 0.8em 0;
  font-weight: 600;
}

.project-description {
  color: #4a5568;
  font-size: 1em;
  line-height: 1.6;
  margin-bottom: 1.2em;
}

.skills-list {
  display: flex;
  flex-wrap: wrap;
  gap: 0.8em;
  margin: 1.2em 0;
}

.skill-tag {
  background: #e3f2fd;
  color: #1976d2;
  padding: 0.4em 1em;
  border-radius: 20px;
  font-size: 0.9em;
  font-weight: 500;
}

.read-more {
  display: inline-flex;
  align-items: center;
  color: #1976d2;
  text-decoration: none;
  font-weight: 500;
  margin-top: 1em;
}

.read-more:hover {
  text-decoration: underline;
}

.read-more::after {
  content: "→";
  margin-left: 0.5em;
}

@media (max-width: 768px) {
  .project-image {
    height: 200px;
  }
  
  .project-content {
    padding: 1.2em;
  }
  
  .project-title {
    font-size: 1.4em;
  }
}
</style>

<div class="projects-container">

<div class="project-card">
![TradeGuardian AI](/images/tradeguardian.jpg){: .project-image}
<div class="project-content">
<h2 class="project-title">TradeGuardian AI</h2>

Developed an AI-powered DeFi trading assistant that enables users to execute crypto trades via natural language through a chatbot interface. Integrated OpenAI for adaptive decision-making, Jupiter Aggregator for pre-trade simulation and on-chain execution, and a custom trust scoring engine to evaluate token safety.

<div class="skills-list">
<span class="skill-tag">Python</span>
<span class="skill-tag">OpenAI</span>
<span class="skill-tag">Blockchain</span>
<span class="skill-tag">NLP</span>
</div>

[Read more](https://github.com/bnb-hack){: .read-more}
</div>
</div>

<div class="project-card">
![NUSGlance](/images/nusglance.jpg){: .project-image}
<div class="project-content">
<h2 class="project-title">NUSGlance Academic Tracker</h2>

Designed and developed a unified academic tracking platform using Vue.js and Firebase to consolidate disparate learning tools into a seamless, centralized dashboard. This streamlined approach improved students' visibility over coursework and task management.

<div class="skills-list">
<span class="skill-tag">Vue.js</span>
<span class="skill-tag">Firebase</span>
<span class="skill-tag">JavaScript</span>
<span class="skill-tag">UI/UX</span>
</div>

[Read more](https://bt3103-7c86e.web.app){: .read-more}
</div>
</div>

<div class="project-card">
![Social Influence](/images/social-influence.jpg){: .project-image}
<div class="project-content">
<h2 class="project-title">Social Influence Analysis</h2>

Developed a simulation of voter behavior on a social graph to evaluate political influence strategies. Built an undirected graph from shared hobbies and modeled daily vote propagation until stabilization using spectral graph theory.

<div class="skills-list">
<span class="skill-tag">Python</span>
<span class="skill-tag">Graph Neural Networks</span>
<span class="skill-tag">NetworkX</span>
<span class="skill-tag">Data Analysis</span>
</div>

[Read more](https://github.com/lydia372/Social-Influence-Optimization-via-Graph-Neural-Networks/tree/main){: .read-more}
</div>
</div>

</div>