---
layout: default
images:
  - image_path: /images/rand7.jpg
  - image_path: /images/rand8.jpg
---

<ul class="photo-gallery">
   {% for image in page.images %}
      <li>
          <img src="{{ image.image_path | prepend: site.baseurl }}" alt="{{ image.title }}" >
      </li>
   {% endfor %}
</ul>