---
layout: page
title: Projects
stitle: Current Projects
permalink: /projects/
description:
nav: true
nav_order: 2
---

<div class="projects">


<!--
<img src="/assets/giff/mavridis_research.gif" class=research onclick="window.open(this.src)" role="button">
-->

<h2 class="category">Learning with Hybrid Systems</h2>


<div class="container">
  <div class="row row-cols-0">
  {%- assign projects = site.projects | where: "category", "hybrid-learning" -%}
  {%- for project in projects -%}
    {% include projects_left.html %}
  {%- endfor %}
  </div>
</div>

<div class="container">
  <div class="row row-cols-0">
  {%- assign projects = site.projects | where: "category", "hybrid-si" -%}
  {%- for project in projects -%}
    {% include projects.html %}
  {%- endfor %}
  </div>
</div>


<h2 class="category">Communication-Aware Control</h2>

Funded by the Swedish Foundation for Strategic Research (SSF) and Ericsson AB.


<br>
<br>

<div class="container">
  <div class="row row-cols-0">
  {%- assign projects = site.projects | where: "category", "camp" -%}
  {%- for project in projects -%}
    {% include projects_left.html %}
  {%- endfor %}
  </div>
</div>




<h2 class="category">Cyber-Physical Systems Security</h2>

<div class="container">
  <div class="row row-cols-0">
  {%- assign projects = site.projects | where: "category", "cps" -%}
  {%- for project in projects -%}
    {% include projects_left.html %}
  {%- endfor %}
  </div>
</div>






<br><br><br>

<h1 class="category">Selected Past Projects</h1>



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






<h2 class="category">Robotics</h2>

<div class="container">
  <div class="row row-cols-0">
  {%- assign projects = site.projects | where: "category", "hrc" -%}
  {%- for project in projects -%}
    {% include projects.html %}
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




<h2 class="category">Intelligent Transportation</h2>

<div class="container">
  <div class="row row-cols-0">
  {%- assign projects = site.projects | where: "category", "itsc21" -%}
  {%- for project in projects -%}
    {% include projects_left.html %}
  {%- endfor %}
  </div>
</div>







</div>





