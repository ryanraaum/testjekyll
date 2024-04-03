---
title: Home
---

Hello, world!

### People

{% for person in site.data.people %}
  - {{ person.name_display }} 

{% endfor %}

This is from the config file: {{ site.nycep.test }}