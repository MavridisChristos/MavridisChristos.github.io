---
layout: page
title: Research
stitle: Selected Projects
permalink: /projects/
description:
nav: true
nav_order: 2
---

<div class="projects">



<img src="/assets/giff/mavridis_research.gif" class=research onclick="window.open(this.src)" role="button">

<h2 class="category">Progressive Learning & System Identification</h2>

<div class="container">
  <div class="row row-cols-0">
  {%- assign projects = site.projects | where: "category", "tnnls22" -%}
  {%- for project in projects -%}
    {% include projects_left.html %}
  {%- endfor %}
  </div>
</div>

<div class="container">
  <div class="row row-cols-0">
  {%- assign projects = site.projects | where: "category", "cdc23" -%}
  {%- for project in projects -%}
    {% include projects_left.html %}
  {%- endfor %}
  </div>
</div>

<h2 class="category">Risk-Sensitive Reinforcement Learning</h2>

<div class="container">
  <div class="row row-cols-0">
  {%- assign projects = site.projects | where: "category", "jair23" -%}
  {%- for project in projects -%}
    {% include projects_left.html %}
  {%- endfor %}
  </div>
</div>

<h2 class="category">Interaction Laws of Networked Systems</h2>

<div class="container">
  <div class="row row-cols-0">
  {%- assign projects = site.projects | where: "category", "tcns22" -%}
  {%- for project in projects -%}
    {% include projects_left.html %}
  {%- endfor %}
  </div>
</div>


<div class="container">
  <div class="row row-cols-0">
  {%- assign projects = site.projects | where: "category", "cdc21" -%}
  {%- for project in projects -%}
    {% include projects_left.html %}
  {%- endfor %}
  </div>
</div>

<div class="container">
  <div class="row row-cols-0">
  {%- assign projects = site.projects | where: "category", "gamesec20" -%}
  {%- for project in projects -%}
    {% include projects_left.html %}
  {%- endfor %}
  </div>
</div>

<h2 class="category">Human-Robot Interaction & Collaboration</h2>

<div class="container">
  <div class="row row-cols-0">
  {%- assign projects = site.projects | where: "category", "iros20" -%}
  {%- for project in projects -%}
    {% include projects_left.html %}
  {%- endfor %}
  </div>
</div>

<div class="container">
  <div class="row row-cols-0">
  {%- assign projects = site.projects | where: "category", "cdc19" -%}
  {%- for project in projects -%}
    {% include projects_left.html %}
  {%- endfor %}
  </div>
</div>

<div class="container">
  <div class="row row-cols-0">
  {%- assign projects = site.projects | where: "category", "ecc18" -%}
  {%- for project in projects -%}
    {% include projects_left.html %}
  {%- endfor %}
  </div>
</div>

<h2 class="category">Intelligent Transportation</h2>

<div class="container">
  <div class="row row-cols-0">
  {%- assign projects = site.projects | where: "category", "itsc21" -%}
  {%- for project in projects -%}
    {% include projects_left.html %}
  {%- endfor %}
  </div>
</div>


<h2 class="category">Recursive Neural Networks</h2>

<div class="container">
  <div class="row row-cols-0">
  {%- assign projects = site.projects | where: "category", "nengo" -%}
  {%- for project in projects -%}
    {% include projects_left.html %}
  {%- endfor %}
  </div>
</div>







</div>





