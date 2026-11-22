---
layout: page
title: Selected work
permalink: /projects/
description: A selection of software and machine-learning projects by Riya Bisht.
---

<div class="detail-page">
  <p class="eyebrow">Selected work</p>
  <p class="detail-intro">A mix of machine learning, web applications, and practical tools—each one built to solve a specific problem.</p>
  {% for project in site.data.projects %}
    {% include project-detail.html project=project %}
  {% endfor %}
</div>
