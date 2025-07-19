---
layout: archive
title: "Publications"
permalink: /fr/publications/
lang: fr
author_profile: true
---

{% if site.author.googlescholar %}
  <div class="wordwrap">Retrouvez mes articles également sur <a href="{{site.author.googlescholar}}">mon profil Google Scholar</a>.</div>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
