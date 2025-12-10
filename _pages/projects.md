---
layout: default
title: Badia Syed - Portfolio
permalink: /projects/
---

<div class="gallery-container">
<div class="project-gallery">
    {% for project in site.projects %}
      <div class="gallery-item">
        <a href="{{ project.url | relative_url }}">
          <img src="{{ project.image | relative_url }}" alt="{{ project.title }}" />
          <h1 class="project-title">{{ project.title }}</h1>
        </a>
      </div>
    {% endfor %}
</div>
</div>