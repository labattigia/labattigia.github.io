---
layout: menu
title: "Menu Natale"
permalink: Menu-Natale/
visible: 1
---

{% assign menu = site.data.menunatale %}

{% for list in menu %}
{{list[0]}}
{% for item in list[1] %}
{{item}}
{% endfor %}
{% endfor %}