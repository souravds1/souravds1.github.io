---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

You can also find my articles on my [Google Scholar](https://scholar.google.com/citations?user=PS_CX0AAAAAJ) profile.

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
