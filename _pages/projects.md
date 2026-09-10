---
layout: page
title: Research
permalink: /research/
description: Selected research projects in computational biology and machine learning.
nav: true
nav_order: 1
horizontal: false
---

<!-- pages/projects.md -->
<div class="projects">
  <h2 class="category">Selected projects</h2>
  {% assign selected_projects = site.projects | where: "featured", true | sort: "importance" %}
  <div class="row row-cols-1 row-cols-md-3">
    {% for project in selected_projects %}
      {% include projects.liquid %}
    {% endfor %}
  </div>

  <h2 class="category">Exploratory projects</h2>
  {% assign exploratory_projects = site.projects | where: "research_section", "exploratory" | sort: "importance" %}
  <div class="row row-cols-1 row-cols-md-3">
    {% for project in exploratory_projects %}
      {% include projects.liquid %}
    {% endfor %}
  </div>

  <h2 class="category">Interdisciplinary projects</h2>
  {% assign collaborative_projects = site.projects | where: "research_section", "collaborative" | sort: "importance" %}
  <div class="row row-cols-1 row-cols-md-3">
    {% for project in collaborative_projects %}
      {% include projects.liquid %}
    {% endfor %}
  </div>
</div>
