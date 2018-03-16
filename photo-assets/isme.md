---
layout: default
images:
  - image_path: /images/group1.jpg
  - image_path: /images/group2.jpg
  - image_path: /images/group2.jpg
  - image_path: /images/goofy.jpg
  - image_path: /images/bike1.jpg
  - image_path: /images/bike2.jpg
  - image_path: /images/bike3.jpg
  - image_path: /images/bike4.jpg
  - image_path: /images/bike5.jpg
  - image_path: /images/bike6.jpg
  - image_path: /images/dance1.jpg
---

<ul class="photo-gallery">
   {% for image in page.images %}
      <li>
          <img src="{{ image.image_path | prepend: site.baseurl }}" alt="{{ image.title }}" >
      </li>
   {% endfor %}
</ul>