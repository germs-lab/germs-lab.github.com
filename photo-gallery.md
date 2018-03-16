---
layout: page
permalink: /photos/
---

{% assign sorted_gallery = site.photo_gallery | sort: 'weight' %}

<ul class="photo-gallery">

  {% for image in sorted_gallery %}
    <li>
      <a href="{{ image.link | prepend: site.baseurl }}">
        <img src="{{ image.image_path | prepend: site.baseurl}}" alt="{{ image.title }}">
      </a>
      <figcaption>{{ image.caption }} </figcaption>
    </li>
  {% endfor %}
</ul>

