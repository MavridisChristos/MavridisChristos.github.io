---
layout: page
permalink: /publications/
title: Publications
stitle: Selected Publications
description: 
jyears: [2023,2022,2021]
cyears: [2023,2022,2021,2020,2019,2018]
byears: [2023]
pyears: [2019]
nav: true
nav_order: 1
---

<span style="font-family:monospace;">
Publications, Book Chapters, and Patents -- (<a href="https://scholar.google.com/citations?user=msjXTH4AAAAJ&hl=en" title="Google Scholar">Google Scholar <i class="ai ai-google-scholar"></i></a>)
</span>

<hr>
## <span style="font-family:monospace;">Journal Papers</span>

<!-- _pages/publications.md -->
<div class="publications">

{%- for y in page.jyears %}
  <h2 class="year">{{y}}</h2>
  {% bibliography -f journals -q @*[year={{y}}]* %}
{% endfor %}

</div>

<hr>
## <span style="font-family:monospace;">Peer-Reviewed Conference Papers</span>

<!-- _pages/publications.md -->
<div class="publications">

{%- for y in page.cyears %}
  <h2 class="year">{{y}}</h2>
  {% bibliography -f conferences -q @*[year={{y}}]* %}
{% endfor %}

</div>

<hr>
## <span style="font-family:monospace;">Book Chapters</span>

<!-- _pages/publications.md -->
<div class="publications">

{%- for y in page.byears %}
  <h2 class="year">{{y}}</h2>
  {% bibliography -f books -q @*[year={{y}}]* %}
{% endfor %}

</div>

<hr>
## <span style="font-family:monospace;">Patents</span>

<!-- _pages/publications.md -->
<div class="publications">

{%- for y in page.pyears %}
  <h2 class="year">{{y}}</h2>
  {% bibliography -f patents -q @*[year={{y}}]* %}
{% endfor %}

</div>





