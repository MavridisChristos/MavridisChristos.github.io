---
layout: about
title: Home
permalink: /
subtitle: Assistant Professor, TU Wien

profile:
  align: left
  image: profile_pic.png #learnCPS-full.png
  image_dark: profile_pic.png #learnCPS-full-night.png # shown instead of image in dark mode
  image_circular: true # crops the image to make it circular
  more_info: >
    <p>Cyber-Physical Systems Research Unit</p>
    <p>Institute of Computer Engineering</p>
    <p>Faculty of Informatics</p>
    <p>TU Wien</p>
    <p style="margin-top: 0.75rem;">Office DE0319 (E191-01)</p>
    <p>Treitlstraße 3, 1040 Vienna, Austria</p>
    <p><i class="fa-solid fa-envelope fa-fw"></i> <span class="address-email">christos.mavridis (at) tuwien.ac.at</span></p>
    <p><i class="fa-solid fa-phone fa-fw"></i> <a href="tel:+43158801740061" class="address-email">+43 1 58801 740061</a></p>

news: false  # the home page shows the latest news in its own section below
latest_posts: false  # includes a list of the newest posts
selected_papers: false # includes a list of papers marked as "selected={true}"
social: true  # includes social icons at the bottom of the page
---

<p>
I am an Assistant Professor at <a target="_blank" rel="noopener noreferrer" href="https://informatics.tuwien.ac.at/orgs/e191-01">TU Wien Informatics</a>, where I lead the <a href="https://learncps.eu"><span class="learncps-wordmark"><span class="learn">Learn</span><span class="cps">CPS</span></span></a> lab. We bring together learning, optimization, and control theory to study and develop intelligent and interacting Cyber-Physical-Human Systems.
</p>
<p>
Before joining TU Wien in 2026, I was a postdoctoral associate at KTH Royal Institute of Technology with Prof. <a target="_blank" rel="noopener noreferrer" href="https://people.kth.se/~kallej/">Karl Henrik Johansson</a>, and PI of a 2-year SSF project in collaboration with Ericsson Research.
I received my Ph.D. in Electrical Engineering from the University of Maryland, College Park, with Prof. <a target="_blank" rel="noopener noreferrer" href="https://ece.umd.edu/clark/faculty/357/John-S-Baras">John S. Baras</a>, and my Diploma in Electrical and Computer Engineering from the National Technical University of Athens with Prof. <a target="_blank" rel="noopener noreferrer" href="https://nyuad.nyu.edu/en/academics/divisions/engineering/faculty/konstantinos-kyriakopoulos.html">Kostas J. Kyriakopoulos</a>.
</p>

<nav class="home-explore" aria-label="Links">
  <div class="home-explore-links home-explore-row">
    <a href="https://informatics.tuwien.ac.at/people/christos-mavridis" class="home-explore-text"><i class="fa-solid fa-building-columns"></i>TU Wien</a>
    <a href="https://learncps.eu" class="home-explore-lab"><img src="{{ '/assets/img/learnCPS-full-night-transparent.png' | relative_url }}" alt="LearnCPS"><i class="fa-solid fa-arrow-up-right-from-square"></i></a>
    <a href="{{ '/cv/' | relative_url }}" class="home-explore-text"><i class="fa-solid fa-file-lines"></i>CV</a>
  </div>
</nav>

<section class="home-news">
  <div class="home-section-head">
    <h2>News</h2>
    <a href="{{ '/news/' | relative_url }}">All news <i class="fa-solid fa-arrow-right"></i></a>
  </div>
  {% include news_list.liquid visible=4 %}
</section>
<!-- 
<nav class="home-explore" aria-label="Explore">
  <div class="home-explore-links">
    <a href="{{ '/projects/' | relative_url }}"><i class="fa-solid fa-diagram-project"></i>Research</a>
    <a href="https://learncps.eu/publications/"><i class="fa-solid fa-book-open"></i>Publications</a>
    <a href="{{ '/teaching/' | relative_url }}"><i class="fa-solid fa-chalkboard-user"></i>Teaching</a>
    <a href="{{ '/cv/' | relative_url }}"><i class="fa-solid fa-file-lines"></i>CV</a>
    <a href="https://learncps.eu" class="home-explore-lab"><i class="fa-solid fa-arrow-up-right-from-square"></i>LearnCPS</a>
  </div>
</nav> -->

<p class="site-credits">
  Lab website: <a href="https://learncps.eu">learncps.eu</a>.
  Powered by <a href="https://jekyllrb.com/">Jekyll</a> with <a href="https://github.com/alshedivat/al-folio">al-folio</a> theme.
  Hosted by <a href="https://pages.github.com/">GitHub Pages</a>.
  <br>
  Last updated: {{ site.time | date: '%B %d, %Y' }}.
</p>
