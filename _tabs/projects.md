---
layout: page
title: Projects
icon: fas fa-laptop-code
order: 2
---

<div class="post-list">
  {% for project in site.data.projects %}
    {% include projects.html project=project %}
  {% endfor %}
</div>