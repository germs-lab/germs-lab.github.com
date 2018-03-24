---
layout: default
permalink: /people/
images: 
  - image_path: /photos-team/howe.jpg
    title: Adina Howe, PhD
    position:  PI
  - image_path: /photos-team/choi.jpg
    title:  Jinlyung Choi, PhD
    position:  Postdoc
  - image_path: /photos-team/lee.jpg
    title:  Jaejin Lee, PhD
    position:  Postdoc
  - image_path:  /photos-team/ma.jpg 
    title:  Lanying Ma, PhD
    position:  Postdoc
  - image_path:  /photos-team/ricker.gif
    title:  Nicole Ricker, PhD
    position:  Postdoc
  - image_path: /photos-team/colgan.jpg
    title:  Phil Colgan
    position:  PhD Student, ABE
  - image_path: /photos-team/flater.jpg
    title:  Jared Flater
    position:  PhD Student
  - image_path: /photos-team/smith.jpg
    title:  Schuyler Smith
    position:  PhD Student, BCB
  - image_path: /photos-team/villanueva.jpg
    title:  Paul Villanueva
    position:  PhD Student, BCB
  - image_path: /photos-team/guyer.jpg
    title: Hannah Guyer
    position:  MS Student, ABE
  - image_path: /photos-team/luo.jpg
    title: Weiquan Luo 
    position:  MS Student, ABE
  - image_path: /photos-team/yang.jpg
    title: Fan Yang, PhD
    position: Past GERMSie
  - image_path: /photos-team/neher.jpg
    title: Tim Neher
    position:  Collaborator, MS Student, ABE
  - image_path: /photos-team/darte.jpg
    title: DARTE AMR Team
    position:  ISU, USDA, Grinnell

---


<div class="row">

  {% for image in page.images %}
  <div class="column">
    <div class="card">
      <img src="{{ image.image_path | prepend: site.baseurl }}" alt="{{ image.title }}" style="width:100%">
      <div class="container">
        <p class="title2">{{ image.title }}</p>
        <p class="title">{{ image.position }}</p>
      </div>
    </div>
  </div>
  {% endfor %}
</div>
