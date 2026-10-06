---
layout: page
title: Conference Calendar
stitle: Conference Calendar
permalink: /conference-calendar/
description:
nav: false
---

<div class="conference-calendar">

<h2> Conference Calendar </h2>
<p class="cal-intro">Submission deadlines and conference dates by research direction. Select a direction below to filter.</p>

{% include conference_calendar.liquid %}

<h2> Conferences </h2>
<p class="cal-intro">All tracked conferences by research direction. Select a direction below to filter.</p>

{% include direction_list.liquid data_key="conference_list" %}

<h2> Journals </h2>
<p class="cal-intro">All tracked journals by research direction. Select a direction below to filter.</p>

{% include direction_list.liquid data_key="journal_list" %}

</div>

<script>
  (function () {
    document.querySelectorAll('.cal-filter-group').forEach(function (group) {
      var buttons = group.querySelectorAll('.cal-filter');
      var rows = group.querySelectorAll('[data-direction]');
      buttons.forEach(function (btn) {
        btn.addEventListener('click', function () {
          buttons.forEach(function (b) { b.classList.remove('active'); });
          btn.classList.add('active');
          var filter = btn.getAttribute('data-filter');
          rows.forEach(function (row) {
            row.style.display = (filter === 'all' || row.getAttribute('data-direction') === filter) ? '' : 'none';
          });
        });
      });
    });
  })();
</script>
