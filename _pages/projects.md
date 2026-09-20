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

.project-card,
.project-card:hover,
.project-card:focus,
.project-card:active {
  text-decoration: none;
  color: inherit;
}

.project-card * {
  text-decoration: none;
}

.project-card h2,
.project-card div,
.project-card span,
.project-card p {
  text-decoration: none;
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

.project-meta {
  font-size: 0.9em;
  color: #718096;
  margin: -0.4em 0 0.9em 0;
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
}
</style>

<div class="projects-container">

<div class="project-card">
<div class="project-image-wrapper">
<img class="project-image" src="/images/fraud-analytics.jpg" alt="Credit Card Fraud Analytics">
</div>
<div class="project-content">
<h2 class="project-title">Credit Card Fraud Analytics</h2>
<div class="project-meta">Aug 2026</div>
<div class="project-description">
Formulated an end-to-end fraud analytics model combining transaction-level feature engineering with supervised and unsupervised machine learning to detect anomalous financial activity. Evaluated model performance and translated fraud signals into actionable insights for real-world risk detection and decision-making.
</div>
<div class="skills-list">
<span class="skill-tag">Machine Learning</span>
<span class="skill-tag">Fraud Detection</span>
<span class="skill-tag">Financial Risk</span>
</div>
</div>
</div>

<div class="project-card">
<div class="project-image-wrapper">
<img class="project-image" src="/images/aniverse.jpg" alt="AniVerse">
</div>
<div class="project-content">
<h2 class="project-title">AniVerse: A Hybrid Deep Learning Anime Recommendation System</h2>
<div class="project-meta">Feb 2026</div>
<div class="project-description">
AniVerse is a multi-modal deep learning recommendation system designed to personalize anime discovery using large-scale user–item interaction data. It combines neural collaborative filtering with transformer-based text embeddings from anime synopses to capture both behavioral and semantic signals.
</div>
<div class="skills-list">
<span class="skill-tag">Deep Learning</span>
<span class="skill-tag">Recommenders</span>
<span class="skill-tag">Transformers</span>
</div>
</div>
</div>

<div class="project-card">
<div class="project-image-wrapper">
<img class="project-image" src="/images/nccs-ai.jpg" alt="NCCS AI Agent">
</div>
<div class="project-content">
<h2 class="project-title">AI Agent for National Cancer Centre Singapore</h2>
<div class="project-meta">Jan 2026</div>
<div class="project-description">
Designed a multi-agent AI-powered analytics system integrating RAG-based semantic search over healthcare data schemas and table relationships to enable scalable natural language-to-SQL analysis. Built automated dashboards and standardized analytical metrics to support anomaly detection, trend analysis, and data-driven insights across diagnostic datasets.
</div>
<div class="skills-list">
<span class="skill-tag">AI Agents</span>
<span class="skill-tag">RAG</span>
<span class="skill-tag">LangGraph</span>
</div>
</div>
</div>

<div class="project-card">
<div class="project-image-wrapper">
<img class="project-image" src="/images/ubs-finai.jpg" alt="UBS FinAI">
</div>
<div class="project-content">
<h2 class="project-title">UBS Tomorrow's Talent Program FinAI</h2>
<div class="project-meta">Dec 2025</div>
<div class="project-description">
Developed a quantitative FX analytics framework combining factor modelling with RAG-based news sentiment analysis to attribute volatility movements. Transformed unstructured news into standardized signals, enabling explainable market analysis.
</div>
<div class="skills-list">
<span class="skill-tag">RAG</span>
<span class="skill-tag">Sentiment Analysis</span>
<span class="skill-tag">Factor Modeling</span>
</div>
</div>
</div>

<div class="project-card">
<div class="project-image-wrapper">
<img class="project-image" src="/images/systematic-trading.webp" alt="Systematic Trading">
</div>
<div class="project-content">
<h2 class="project-title">Systematic Trading Strategy Development</h2>
<div class="project-meta">Oct 2025</div>
<div class="project-description">
Developed and backtested volatility-aware trend-following and Keltner breakout strategies with regime filters and portfolio-level risk targeting on MAANG equities.
</div>
<div class="skills-list">
<span class="skill-tag">Python</span>
<span class="skill-tag">Time Series</span>
<span class="skill-tag">Risk Targeting</span>
</div>
</div>
</div>

<a class="project-card" href="https://bschool.nus.edu.sg/cgs/wp-content/uploads/sites/145/2026/01/Proceedings-of-Tencent-CGS-Academic-Conference-2025_Volume-II_Poster-Submissions.pdf">
<div class="project-image-wrapper">
<img class="project-image" src="/images/global-voices.png" alt="Global Voices in Play">
</div>
<div class="project-content">
<h2 class="project-title">Global Voices in Play (LLM-Driven Youth Gaming Addiction Analysis)</h2>
<div class="project-meta">Jul 2025 – Nov 2025</div>
<div class="project-description">
Published at the 2025 Global Open Research Competition (Tencent x NUS). Built an LLM-driven multilingual analysis pipeline using embedding-space modeling, supervised sentiment classification, affect-keyword mapping, unsupervised clustering, and large-scale social media scraping to generate cross-cultural digital well-being insights.
</div>
<div class="skills-list">
<span class="skill-tag">LLMs</span>
<span class="skill-tag">Multilingual NLP</span>
<span class="skill-tag">Clustering</span>
</div>
</div>
</a>

</div>
