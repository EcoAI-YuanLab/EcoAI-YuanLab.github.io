---
layout: page
title: Research
permalink: /Research/
nav: true
nav_order: 1
display_categories: [Selected Projects]
horizontal: false
---

<img src="/assets/img/research_banner.png" alt="Research banner"
     style="width:100%; max-height:420px; object-fit:cover; border-radius:12px; margin-bottom:16px;">



Ecosystems play a crucial role in climate regulation by mediating carbon, water, and energy exchanges with the atmosphere. At the same time, climate and human activities are reshaping ecosystem structure, composition, and functioning. We study how ecosystems respond to and influence climate dynamics and disturbances (e.g., wildfire, deforestation, flooding) through biogeochemical and biophysical processes. Our goal is to assess ecological and climate risks, and advance nature-based solutions to enhance the benefits of ecosystem services. 
<!-- pages/projects.md -->
<div class="projects">
{% if site.enable_project_categories and page.display_categories %}
  <!-- Display categorized projects -->
  {% for category in page.display_categories %}
  <a id="{{ category }}" href=".#{{ category }}">
    <h2 class="category" style="text-align:left; color:#000; font-weight:200;">{{ category }}</h2>
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
