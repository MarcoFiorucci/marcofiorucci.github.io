    ---
layout: page
title: projects
permalink: /projects/
description: A growing collection of my research projects and publications.
nav: true
nav_order: 2
display_categories: [research]
horizontal: false
---

<!-- Categoria dei progetti -->
<div class="projects">
{% if site.enable_project_categories and page.display_categories %}
  <!-- Display categorised projects -->
  {% for category in page.display_categories %}
  <h2 class="category">{{ category }}</h2>
  {% assign categorized_projects = site.projects | where: "category", category %}
  {% assign sorted_projects = categorized_projects | sort: "importance" %}

  <div class="grid">
    {% for project in sorted_projects %}
      {% include projects.liquid %}
    {% endfor %}
  </div>
  {% endfor %}

{% else %}
  <!-- Display projects without categories -->
  {% assign sorted_projects = site.projects | sort: "importance" %}

  <div class="grid">
    {% for project in sorted_projects %}
      {% include projects.liquid %}
    {% endfor %}
  </div>
{% endif %}
</div>