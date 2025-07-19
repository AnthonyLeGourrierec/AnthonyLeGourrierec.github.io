---
title: "Exemples de mise en page"
layout: archive
permalink: /fr/archive-layout-with-content/
lang: fr
---

Cette page présente divers exemples de mise en forme proposés par le thème.

# Titre de niveau un

## Titre de niveau deux

### Titre de niveau trois

{% include base_path %}
{% for post in site.pages %}
  {% include archive-single.html %}
{% endfor %}
