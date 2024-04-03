---
title: Home
---

Hello, world!

### People

{% for person in site.data.people %}
  - {{ person | inspect }} 

{% endfor %}

This is from the config file: {{ site.nycep.test }}