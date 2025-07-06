---
layout: archive
title: "Research Thrust"
permalink: /portfolio/research-thrust/
author_profile: true
---
 
{% assign projects = site.portfolio | where: "category", "research-thrust" | reverse %}
{% for post in projects %}
  {% include archive-single.html %}
{% endfor %}
