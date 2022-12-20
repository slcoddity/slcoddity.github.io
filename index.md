---
layout: default
title: "Intro"
---
Hello, this will be the palce where I share my technical art works, comments/questions are welcome (12/20/2022).

{% if site.show_excerpts %}
  {% include home.html %}
{% else %}
  {% include archive.html title="Posts" %}
{% endif %}
