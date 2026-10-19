---
layout: page
title: 项目
permalink: /zh/projects/
nav: true
nav_order: 3
horizontal: false
_styles: >
  .projects .card-title { font-size: 1.4rem; line-height: 1.3; }
---

<div class="projects">
{% assign sorted_projects = site.projects_zh | sort: "importance" %}
  <div class="row row-cols-1 row-cols-md-2">
    {% for project in sorted_projects %}
      {% include projects.liquid %}
    {% endfor %}
  </div>
</div>
