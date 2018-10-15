---
layout: default
permalink: /people/
images: 
  - image_path: /photos-team/howe.jpg
    title: Adina Howe, PhD
    position:  PI
    website: 
  - image_path: /photos-team/choi.jpg
    title:  Jinlyung Choi, PhD
    position:  Postdoc
    website: 
  - image_path: /photos-team/lee.jpg
    title:  Jaejin Lee, PhD
    position:  Postdoc
    website: 
  - image_path:  /photos-team/ma.jpg 
    title:  Lanying Ma, PhD
    position:  Postdoc
    website: 
  - image_path:  /photos-team/ricker.jpg
    title:  Nicole Ricker, PhD
    position:  Postdoc
    website: 
  - image_path: /photos-team/alt.jpg
    title:  Laura Alt
    position:  PhD Student
    website: 
  - image_path: /photos-team/colgan.jpg
    title:  Phil Colgan
    position:  PhD Student
    website: 
  - image_path: /photos-team/flater.jpg
    title:  Jared Flater
    position:  PhD Student
    website: 
  - image_path: /photos-team/smith.jpg
    title:  Schuyler Smith
    position:  PhD Student
    website: https://schuyler-smith.github.io/
  - image_path: /photos-team/villanueva.jpg
    title:  Paul Villanueva
    position:  PhD Student
    website: 
  - image_path: /photos-team/guyer.jpg
    title: Hannah Guyer
    position:  MS Student
    website: 
  - image_path: /photos-team/dolphin.jpg
    title: Chad Dolphin
    position:  MS Student
    website: 
  - image_path: /photos-team/luo.jpg
    title: Weiquan Luo 
    position:  MS Student
    website: 
  - image_path: /photos-team/yang.jpg
    title: Fan Yang, PhD
    position: Past GERMSie
    website: 
  - image_path: /photos-team/ed.jpg
    title: Ed Lopatto
    position:  Honorary GERMS
    website: 
  - image_path: /photos-team/neher.jpg
    title: Tim Neher
    position:  Honorary GERMS


---


<div class="row">
  {% for image in page.images %}
  <div class="column">
    <div class="card">
        {% if image.website %}
          <a href="{{ image.website }}" target="_blank" style="text-decoration: none">
        {% endif %}
        <img src="{{ image.image_path | prepend: site.baseurl }}" alt="{{ image.title }}" style="width:100%">
      <div class="container">
        <p class="title2" style="padding-top: 10px; margin-bottom: 0px">{{ image.title }}</p>
        <p class="title" style="margin: 0 ; {% if image.website == null %}padding-bottom: 27px{% endif %};">{{ image.position }}</p>
        {% if image.website %}
          <p class="title" style="margin-top: -4px; margin-bottom: 4px">Personal Website</p> 
        {% endif %}
      </div>
      {% if image.website %}
        </a>
      {% endif %}
    </div>
  </div>
  {% endfor %}
</div>
