---
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults
layout: page
title: Latest
---
![PC-98 game image](/assets/grounseed.jpg)

{% for pc-98 in site.pc-98 %}
  <p>{{ pc-98.content | markdownify }}</p>
{% endfor %}
