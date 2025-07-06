---
layout: archive
title: "Project Portfolio"
permalink: /portfolio/
author_profile: true
---

<div class="grid__wrapper">
  <div class="grid__item">
    <h2 class="archive__subtitle">Research Thrust</h2>
    {% assign research_projects = site.portfolio | where: "category", "research-thrust" | reverse %}
    <ul>
      {% for post in research_projects %}
        <li><a href="{{ post.url | relative_url }}">{{ post.title }}</a></li>
      {% endfor %}
    </ul>
  </div>
  <div class="grid__item">
    <h2 class="archive__subtitle">Graduate Course Projects</h2>
    {% assign course_projects = site.portfolio | where: "category", "course-projects" | reverse %}
    <ul>
      {% for post in course_projects %}
        <li><a href="{{ post.url | relative_url }}">{{ post.title }}</a></li>
      {% endfor %}
    </ul>
  </div>
</div>
