---
layout: default
permalink: /people/
images: 
  - image_path: /photos-team/howe.jpg
    title: Adina Howe
    position:  PI
    weight: 1
  - image_path: /photos-team/choi.jpg
    title:  Jinlyung Choi, PhD
    position:  Postdoc
    weight: 2
  - image_path: /photos-team/lee.jpg
    title:  Jaejin Lee, PhD
    position:  Postdoc
    weight: 2
  - image_path: /photos-team/ma.jpg
    title:  Lanying Ma, PhD
    position:  Postdoc
    weight: 2
  - image_path: /photos-team/smith.jpg
    title:  Schuyler Smith
    position:  PhD Student, BCB
    weight: 2
  - image_path: /photos-team/guyer.jpg
    title: Hannah Guyer
    position:  MS Student, ABE
    weight: 4

---


<div class="row">

  {% for image in page.images %}
  <div class="column">
    <div class="card">
      <img src="{{ image.image_path | prepend: site.baseurl }}" alt="{{ image.title }}" style="width:100%">
      <div class="container">
        <h2>{{ image.title }}</h2>
        <p class="title">{{ image.position }}</p>
      </div>
    </div>
  </div>
  {% endfor %}
</div>
