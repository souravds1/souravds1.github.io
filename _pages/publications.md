---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---
You can also find my articles on my [Google Scholar](https://scholar.google.com/citations?user=QTb8X1kAAAAJ&hl=en) profile.
{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
