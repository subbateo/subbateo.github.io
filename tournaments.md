---
layout: page
title: Tornei
---

## Elenco dei tornei

{% for tournament in site.tournaments %}
  - [{{ tournament.title }}]({{ tournament.url }})
{% endfor %}

---

## Nuovo torneo

<iframe src="https://docs.google.com/forms/d/e/1FAIpQLSf8sjuYCFE5V1O5P29yCv3hraWnnwSNZZnuNePcX3QIaH-h3Q/viewform?embedded=true" width="100%" height="1000" frameborder="0" marginheight="0" marginwidth="0">Caricamento in corso...</iframe>

