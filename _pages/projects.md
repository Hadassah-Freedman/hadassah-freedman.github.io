---
layout: splash
title: "Projects"
permalink: /projects/
---

<div class="projects-grid">
  {% for project in site.data.projects %}
  <a href="{{ project.url }}" class="project-card">
    <div class="project-img" style="background-image: url('{{ project.image }}');">
      <div class="project-overlay">
        <span>{{ project.title }}</span>
      </div>
    </div>
  </a>
  {% endfor %}
</div>
