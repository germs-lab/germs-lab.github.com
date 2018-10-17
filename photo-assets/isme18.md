---
layout: default
images:
  - image_path: /images/isme18/0.jpg
  - image_path: /images/isme18/4.jpg
  - image_path: /images/isme18/7.jpg
  - image_path: /images/isme18/14.jpg
  - image_path: /images/isme18/18.jpg
  - image_path: /images/isme18/20.jpg
  - image_path: /images/isme18/22.jpg
  - image_path: /images/isme18/23.jpg
  - image_path: /images/isme18/24.jpg
  - image_path: /images/isme18/25.jpg
  - image_path: /images/isme18/26.jpg
  - image_path: /images/isme18/27.jpg
  - image_path: /images/isme18/28.jpg
  - image_path: /images/isme18/29.jpg
  - image_path: /images/isme18/30.jpg
  - image_path: /images/isme18/31.jpg
  - image_path: /images/isme18/32.jpg

---

<ul class="photo-gallery">
   {% for image in page.images %}
      <li>
          <img src="{{ image.image_path | prepend: site.baseurl }}" alt="{{ image.title }}" >
      </li>
   {% endfor %}
</ul>