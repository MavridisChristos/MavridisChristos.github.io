---
layout: page
title: Conferences and Journals
stitle: Conferences and Journals
permalink: /conference-calendar/
description:
nav: false
---

<div class="conference-calendar">

<h2> Conference Calendar </h2>
<p class="cal-intro">Submission deadlines and conference dates by research direction. Select a direction below to filter.</p>

{% include conference_calendar.liquid %}

<br>
<br>

<h2> Conferences </h2>
<p class="cal-intro">All tracked conferences by research direction. Select a direction below to filter.</p>

{% include direction_list.liquid data_key="conference_list" %}

<br>
<br>

<h2> Journals </h2>
<p class="cal-intro">All tracked journals by research direction. Select a direction below to filter.</p>

{% include direction_list.liquid data_key="journal_list" %}

</div>

<script>
  (function () {
    // Direction buttons toggle independently, so several can be active at
    // once. "All" clears the selection; deselecting the last direction
    // falls back to "All".
    document.querySelectorAll('.cal-filter-group').forEach(function (group) {
      var allBtn = group.querySelector('.cal-filter[data-filter="all"]');
      var dirBtns = group.querySelectorAll('.cal-filter:not([data-filter="all"])');
      var rows = group.querySelectorAll('[data-direction]');

      function apply() {
        var selected = [];
        dirBtns.forEach(function (b) {
          if (b.classList.contains('active')) selected.push(b.getAttribute('data-filter'));
        });
        allBtn.classList.toggle('active', selected.length === 0);
        rows.forEach(function (row) {
          var show = selected.length === 0 || selected.indexOf(row.getAttribute('data-direction')) !== -1;
          row.style.display = show ? '' : 'none';
        });
      }

      allBtn.addEventListener('click', function () {
        dirBtns.forEach(function (b) { b.classList.remove('active'); });
        apply();
      });
      dirBtns.forEach(function (btn) {
        btn.addEventListener('click', function () {
          btn.classList.toggle('active');
          apply();
        });
      });
    });
  })();
</script>
