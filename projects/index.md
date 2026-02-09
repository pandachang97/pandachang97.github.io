---
title: Projects
---

<ul>
{% for p in site.data.projects %}
  <li><a href="{{ p.url }}">{{ p.name }}</a> — {{ p.desc }}</li>
{% endfor %}
</ul>
