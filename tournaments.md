---
layout: page
title: Tornei
---

## Elenco dei tornei

{% for tournament in site.tournaments %}
  - [{{ tournament.title }}]({{ tournament.url }})
{% endfor %}
