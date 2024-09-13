---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

Puedes encontrar el artículo en: <u><a href="https://scholar.google.com/citations?user=aMdEAVwAAAAJ&hl=es">my Google Scholar profile</a>.</u>



{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
