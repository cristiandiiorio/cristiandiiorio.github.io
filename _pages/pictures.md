---
layout: page
title: photography
permalink: /photography/
nav: true
nav_order: 5
---

<div class="row row-cols-1 row-cols-md-2 g-4">
  {% assign pictures = site.static_files | where_exp: "file", "file.path contains '/assets/img/pictures/'" | sort: "name" | reverse %}
  {% for pic in pictures %}
  <div class="col">
    <a href="{{ pic.path | relative_url }}" data-lightbox="gallery" data-title="{{ pic.name }}">
      {% include figure.liquid loading="eager" path=pic.path class="img-fluid rounded z-depth-1" alt=pic.name %}
    </a>
  </div>
  {% endfor %}
</div>