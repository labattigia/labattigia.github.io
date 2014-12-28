---
layout: menu
title: "Menu Pasqua"
permalink: Menu-Pasqua/
visible: 1
---

{% assign menu = site.data.menupasqua %}

{% for list in menu %}
{{list[0]}}
{% for item in list[1] %}
{{item}}
{% endfor %}
{% endfor %}