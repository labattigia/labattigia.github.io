---
layout: menu
title: "Menu Capodanno"
permalink: Menu-Capodanno/
visible: 1
---

{% assign menu = site.data.menucapodanno %}

{% for list in menu %}
{{list[0]}}
{% for item in list[1] %}
{{item}}
{% endfor %}
{% endfor %}