---
layout: page
title: Research
stitle: Research Interests
permalink: /projects/
description:
nav: true
nav_order: 1
# Card lists below; icons are Font Awesome "solid" names (https://fontawesome.com/search?s=solid)
foundations:
  - { title: Hybrid systems theory, icon: fa-shuffle }
  - { title: Stochastic optimization, icon: fa-dice }
  - { title: Robust and risk-sensitive control, icon: fa-shield-halved }
  - { title: Knowledge representation and reasoning, icon: fa-lightbulb }
  - { title: Group-invariant and hierarchical topologies, icon: fa-layer-group }
  - { title: Homotopy optimization and bifurcation theory, icon: fa-code-branch }
applications:
  - { title: "Robotics, Autonomous Vehicles, UAVs", icon: fa-robot }
  - { title: Explainable AI & Learning-based Control, icon: fa-brain }
  - { title: Human-Robot Interaction & Collaboration, icon: fa-handshake }
  - { title: Risk-Sensitive Reinforcement Learning, icon: fa-chart-line }
  - { title: Communication-aware Robotics, icon: fa-tower-broadcast }
  - { title: Swarm Dynamics Identification, icon: fa-circle-nodes }
  - { title: Intelligent Transportation, icon: fa-car }
  - { title: Smart Cities, icon: fa-city }
---

<div class="lcps-research">

<div class="lcps-mission">
  <p>I am interested in inference and control problems in complex <strong>Cyber-Physical-Human Systems</strong>, from autonomous cars to UAV swarms, and from industrial robots to collaborative human-robot systems.</p>
</div>

<h2 class="lcps-section">Foundations</h2>
<p class="lcps-lead">My main focus is on the analysis of the underlying learning algorithms using principles from:</p>
<div class="lcps-grid lcps-grid-3">
  {% for f in page.foundations %}
  <div class="lcps-card lcps-card-compact" style="--c: #3B6EA8">
    <h4><i class="fa-solid {{ f.icon }}"></i>{{ f.title }}</h4>
  </div>
  {% endfor %}
</div>

<h2 class="lcps-section">Applications</h2>
<p class="lcps-lead">Beyond fundamental research on Optimization, Learning Theory, (Hybrid) Systems and Control Theory, and Multi-Agent Systems, I am interested in a wide range of applications, including:</p>
<div class="lcps-grid lcps-grid-4">
  {% for a in page.applications %}
  <div class="lcps-card lcps-card-compact" style="--c: #C47A1E">
    <h4><i class="fa-solid {{ a.icon }}"></i>{{ a.title }}</h4>
  </div>
  {% endfor %}
</div>

</div>

<p class="lab-pill-row">
  <a class="lab-pill" href="https://learncps.eu">
    <img src="{{ '/assets/img/learnCPS-full-night-transparent.png' | relative_url }}" alt="LearnCPS">
    <span>learncps.eu <i class="fa-solid fa-arrow-up-right-from-square"></i></span>
  </a>
</p>
