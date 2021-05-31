---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

You can find the full list of my articles on <u><a href="https://scholar.google.com/citations?user=XPaxiK8AAAAJ&hl=en">my Google Scholar profile</a></u>. I only list the articles which aren't open-access or contain additional resources here.

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
