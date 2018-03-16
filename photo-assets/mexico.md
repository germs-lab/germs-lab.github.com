---
layout: default
images:
  - image_path: /images/mex1.jpg
  - image_path: /images/mex2.jpg
  - image_path: /images/mex3.jpg
  - image_path: /images/mex4.jpg
---

<ul class="photo-gallery">
   {% for image in page.images %}
      <li>
          <img src="{{ image.image_path | prepend: site.baseurl }}" alt="{{ image.title }}" >
      </li>
   {% endfor %}
</ul>