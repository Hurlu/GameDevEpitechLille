---
title: Fiches Techniques
permalink: /fiches/
layout: page
---

Et là y'aura des fiches techniques !

{% for fiche in site.fiches %}
   {{ fiche.title }}
   {{ fiche.content }}
{% endfor %}