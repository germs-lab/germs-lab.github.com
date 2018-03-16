---
layout: default
images:
  - image_path: /images/germs_v0.jpg
  - image_path: /images/rand2.jpg
  - image_path: /images/rand3.jpg
  - image_path: /images/rand4.jpg
  - image_path: /images/rand5.jpg
  - image_path: /images/rand6.jpg
---

<ul class="photo-gallery">
   {% for image in page.images %}
      <li>
          <img src="{{ image.image_path | prepend: site.baseurl }}" alt="{{ image.title }}" >
      </li>
   {% endfor %}
</ul>