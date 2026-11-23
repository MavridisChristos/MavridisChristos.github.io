---
layout: page
title: Teaching
stitle: Teaching
permalink: /teaching/
description:
nav: true
nav_order: 2
courses:
  - title: Stochastic Foundations of Cyber-Physical Systems
    icon: fa-chalkboard-user
    # TODO: replace with the real course description from TISS
    text: Bayesian Inference, Markov Decision Processes, Supervised, Unsupervised, and Reinforcement Learning. Applications in speech recognition and robotics.
    tags: [182.763, 2026W, VU, 4.0h, 6.0 ECTS]
    url: https://tiss.tuwien.ac.at/course/courseDetails.xhtml?dswid=6924&dsrid=456&semester=2026W&courseNr=182763
---

<div class="lcps-research">

<h2 class="lcps-section">TU Wien Informatics</h2>
<div class="lcps-grid">
  {% for c in page.courses %}
  <div class="lcps-card lcps-course" style="--c: #3B6EA8">
    <h4><i class="fa-solid {{ c.icon }}"></i>{{ c.title }}</h4>
    <p>{{ c.text }}</p>
    <div class="lcps-course-foot">
      <div class="lcps-tags">{% for t in c.tags %}<span>{{ t }}</span>{% endfor %}</div>
      <a class="lcps-btn lcps-btn-outline" href="{{ c.url }}">Course page (TISS) <i class="fa-solid fa-arrow-up-right-from-square"></i></a>
    </div>
  </div>
  {% endfor %}
</div>

<p class="lcps-lead lcps-teaching-note">
  For more information visit <a href="https://informatics.tuwien.ac.at/people/christos-mavridis">my TU Wien page</a>.
</p>

</div>
