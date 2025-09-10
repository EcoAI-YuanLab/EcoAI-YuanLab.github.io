---
layout: page
title: Research
permalink: /projects/
nav: true
nav_order: 3
display_categories: [Selected Projects]
horizontal: false
---

<img src="/assets/img/research_banner.png" alt="Research banner"
     style="width:100%; max-height:420px; object-fit:cover; border-radius:12px; margin-bottom:16px;">


#### Overview
Ecosystems play a crucial role in climate regulation by modulating carbon, water, and energy exchanges with the atmosphere. At the same time, climate and human activities are reshaping ecosystem structure, composition, and functioning. ​My research aims to better understand how ecosystems respond to and influence climate dynamics and disturbances, supporting more reliable projections and the development of nature-based solutions.  ​I am particularly interested in (1) wetland biogeochemical cycles affecting atmospheric greenhouse gas dynamics; and (2) ecosystem biophysical processes determining temperature and water availability in the context of disturbances (e.g., land-use and land-cover change, deforestation, drought, and wildfires). Additionally, I also develop (3) advanced hybrid AI algorithms that harmonize data-driven machine learning and knowledge-driven Earth system models to better understand the complex ecosystem-climate-human interactions from a causal-effect perspective.

<!-- pages/projects.md -->
<div class="projects">
{% if site.enable_project_categories and page.display_categories %}
  <!-- Display categorized projects -->
  {% for category in page.display_categories %}
  <a id="{{ category }}" href=".#{{ category }}">
    <h2 class="category">{{ category }}</h2>
  </a>
  {% assign categorized_projects = site.projects | where: "category", category %}
  {% assign sorted_projects = categorized_projects | sort: "importance" %}
  <!-- Generate cards for each project -->
  {% if page.horizontal %}
  <div class="container">
    <div class="row row-cols-1 row-cols-md-2">
    {% for project in sorted_projects %}
      {% include projects_horizontal.liquid %}
    {% endfor %}
    </div>
  </div>
  {% else %}
  <div class="row row-cols-1 row-cols-md-2">
    {% for project in sorted_projects %}
      {% include projects.liquid %}
    {% endfor %}
  </div>
  {% endif %}
  {% endfor %}

{% else %}

<!-- Display projects without categories -->

{% assign sorted_projects = site.projects | sort: "importance" %}

  <!-- Generate cards for each project -->

{% if page.horizontal %}

  <div class="container">
    <div class="row row-cols-1 row-cols-md-2">
    {% for project in sorted_projects %}
      {% include projects_horizontal.liquid %}
    {% endfor %}
    </div>
  </div>
  {% else %}
  <div class="row row-cols-1 row-cols-md-3">
    {% for project in sorted_projects %}
      {% include projects.liquid %}
    {% endfor %}
  </div>
  {% endif %}
{% endif %}
</div>
