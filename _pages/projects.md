---
layout: single
title: "Projects"
permalink: /projects/
author_profile: true
classes: wide
---

<style>
.projects-container {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
  gap: 2em;
  margin-top: 2em;
}

.project-card {
  background: white;
  border-radius: 15px;
  overflow: hidden;
  box-shadow: 0 4px 6px rgba(0,0,0,0.1);
  transition: transform 0.2s ease, box-shadow 0.2s ease;
}

.project-card:hover {
  transform: translateY(-5px);
  box-shadow: 0 6px 12px rgba(0,0,0,0.15);
}

.project-image {
  width: 100%;
  height: 200px;
  object-fit: cover;
  border-bottom: 1px solid #eee;
}

.project-content {
  padding: 1.5em;
}

.project-title {
  font-size: 1.4em;
  color: #2c3e50;
  margin: 0 0 0.5em 0;
}

.project-title a {
  color: #2c3e50;
  text-decoration: none;
}

.project-title a:hover {
  color: #3498db;
}

.project-description {
  color: #666;
  font-size: 0.95em;
  line-height: 1.6;
  margin-bottom: 1em;
}

.skills-list {
  display: flex;
  flex-wrap: wrap;
  gap: 0.5em;
  margin-top: 1em;
}

.skill-tag {
  background: #f0f4f8;
  color: #3498db;
  padding: 0.3em 0.8em;
  border-radius: 15px;
  font-size: 0.85em;
  font-weight: 500;
}

.read-more {
  display: inline-block;
  margin-top: 1em;
  color: #3498db;
  text-decoration: none;
  font-weight: 500;
}

.read-more:hover {
  text-decoration: underline;
}
</style>

<div class="projects-container" markdown="1">

<div class="project-card" markdown="1">
![TradeGuardian AI](/images/tradeguardian.jpg){: .project-image}
<div class="project-content">
### [TradeGuardian AI](https://github.com/bnb-hack)
{: .project-title}

Developed an AI-powered DeFi trading assistant that enables users to execute crypto trades via natural language through a chatbot interface. Integrated OpenAI for adaptive decision-making, Jupiter Aggregator for pre-trade simulation and on-chain execution, and a custom trust scoring engine to evaluate token safety.

<div class="skills-list">
<span class="skill-tag">Python</span>
<span class="skill-tag">OpenAI</span>
<span class="skill-tag">Blockchain</span>
<span class="skill-tag">NLP</span>
</div>

[Read more →](https://github.com/bnb-hack){: .read-more}
</div>
</div>

<div class="project-card" markdown="1">
![NUSGlance](/images/nusglance.jpg){: .project-image}
<div class="project-content">
### [NUSGlance Academic Tracker](https://bt3103-7c86e.web.app)
{: .project-title}

Designed and developed a unified academic tracking platform using Vue.js and Firebase to consolidate disparate learning tools into a seamless, centralized dashboard. This streamlined approach improved students' visibility over coursework and task management.

<div class="skills-list">
<span class="skill-tag">Vue.js</span>
<span class="skill-tag">Firebase</span>
<span class="skill-tag">JavaScript</span>
<span class="skill-tag">UI/UX</span>
</div>

[Read more →](https://bt3103-7c86e.web.app){: .read-more}
</div>
</div>

<div class="project-card" markdown="1">
![Social Influence](/images/social-influence.jpg){: .project-image}
<div class="project-content">
### [Social Influence Analysis](https://github.com/lydia372/Social-Influence-Optimization-via-Graph-Neural-Networks/tree/main)
{: .project-title}

Developed a simulation of voter behavior on a social graph to evaluate political influence strategies. Built an undirected graph from shared hobbies and modeled daily vote propagation until stabilization using spectral graph theory.

<div class="skills-list">
<span class="skill-tag">Python</span>
<span class="skill-tag">Graph Neural Networks</span>
<span class="skill-tag">NetworkX</span>
<span class="skill-tag">Data Analysis</span>
</div>

[Read more →](https://github.com/lydia372/Social-Influence-Optimization-via-Graph-Neural-Networks/tree/main){: .read-more}
</div>
</div>

</div>