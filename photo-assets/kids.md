---
layout: default
images:
  - image_path: /images/grinnell.jpg
  - image_path: /images/rand9.jpg
  - image_path: /images/care0.gif
  - image_path: /images/care1.gif
  - image_path: /images/care2.gif
  - image_path: /images/care3.gif
---

<ul class="photo-gallery">
   {% for image in page.images %}
      <li>
          <img src="{{ image.image_path | prepend: site.baseurl }}" alt="{{ image.title }}" >
      </li>
   {% endfor %}
</ul>