---
layout: minimal
permalink: /family/photo-restoration/
title: "Photo Restoration"
excerpt: "Comparing original photos with colorized and enhanced versions."
collection: portfolio
date: 2024-07-20
tags: [Image Restoration, Photo Editing, Portfolio]
image: /images/Photo_restoration/after/img760_RealESRGAN_x2_00001_.png
hidden: true
---

# Restoration photos Le Gourriérec

<link rel="stylesheet" href="https://cdn.knightlab.com/libs/juxtapose/latest/css/juxtapose.css">
<script src="https://cdn.knightlab.com/libs/juxtapose/latest/js/juxtapose.js" defer></script>

<div class="restoration-gallery">
{% assign before_images = site.static_files | where_exp: "file", "file.path contains '/images/Photo_restoration/before'" | sort: "path" %}
{% assign after_images = site.static_files | where_exp: "file", "file.path contains '/images/Photo_restoration/after'" | sort: "path" %}
{% for before in before_images %}
  {% assign after = after_images[forloop.index0] %}
  <div class="juxtapose" data-startingposition="50%" data-showlabels="true" data-showcredits="false">
    <img src="{{ before.path | relative_url }}" alt="Before {{ before.name }}" />
    <img src="{{ after.path | relative_url }}" alt="After {{ after.name }}" />
  </div>
{% endfor %}
</div>

<style>
.restoration-gallery {
  display: flex;
  flex-direction: column;
  gap: 2rem;
}

.juxtapose {
  width: 100%;
  max-width: 800px;
  margin: 0 auto;
}

.juxtapose img {
  width: 100%;
  height: auto;
}
</style>
