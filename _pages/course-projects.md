---
layout: archive
title: "Graduate Course Projects"
permalink: /portfolio/course-projects/
author_profile: true
---

{% assign projects = site.portfolio | where: "category", "course-projects" | reverse %}
{% for post in projects %}
  {% include archive-single.html %}
{% endfor %}
