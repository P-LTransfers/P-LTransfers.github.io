---
layout: page
title: Najnowsze Transfery
---

<ul>
{% for item in site.data.transfery %}
  <li style="{% if item.value > "20" %}color: blue {% endif %}">
  {{ item.name }} <em> {{item.position}}</em>
  </li>
{% endfor %}
</ul>
