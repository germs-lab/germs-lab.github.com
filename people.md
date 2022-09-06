---
layout: default
permalink: /people/
github: /\_photo_gallery/github.png
current_images: 
  - image_path: /photos-team/Howe_Adina304.png
    title: Adina Howe, PhD 
    position:  PI
    website: https://github.com/germs-lab
    
  - image_path: /photos-team/lee.jpg
    title:  Jaejin Lee, PhD
    position:  Research Scientist
    
  - image_path:  /photos-team/lorien.jpg
    title:  Lorien Radmer, MS
    position:  Research Scientist
 
  - image_path: /photos-team/alt.jpg
    title:  Laura Alt, PhD
    position:  Postdoc
    
  - image_path: /photos-team/michael.jpg
    title:  Michael Millican, PhD
    position:  Postdoc
    
  - image_path: /photos-team/flater.jpg
    title:  Jared Flater, PhD
    position:  Postdoc
    
  - image_path: /photos-team/jihoon2.jpg
    title: Jihoon Yang, PhD
    position:  Postdoc
    
  - image_path: /photos-team/puja2.jpg
    title:  Puja Bajracharya
    position:  PhD Student (BCB)

  - image_path: /photos-team/grace.jpg
    title:  Grace Carey 
    position:  PhD Student (Micro)
    
  - image_path: /photos-team/liu.jpg
    title:  Jia Liu
    position:  PhD Student (BCB)
    website:  https://github.com/jialiu232

  - image_path: /photos-team/villanueva.jpg
    title:  Paul Villanueva
    position:  PhD Student (BCB)
    website: https://github.com/pommevilla?tab=repositories

  - image_path: /photos-team/kaija.jpg
    title: Kaija Dahlberg
    position:  Undergraduate RA

  - image_path: /photos-team/juliana.jpg
    title: Juliana Johnson
    position:  Undergraduate RA
    
  - image_path: /photos-team/e.jpg
    title: Emma Nieland
    position:  Undergraduate RA
    
  - image_path: /photos-team/erik.jpg
    title: Erik Raman
    position:  Undergraduate RA


---
<div class="row">
  {% for image in page.current_images %}
  <div class="column">
    <div class="card">
      {% if image.website %}<a href="{{ image.website }}" target="_blank" style="text-decoration: none">{% endif %}
      <img src="{{ image.image_path | prepend: site.baseurl }}" alt="{{ image.title }}" style="width:100%">
      <div class="container">
        <p class="title2" style="padding-top: 10px; margin-bottom: 0px">{{ image.title }}</p>
        <p class="title" style="padding-bottom: 10px;">{{ image.position }}
        {% if image.website %}<span style="float:right; position: relative; top: -15%;"><img src="/photos-team/github.png" alt="{{ image.title }}" style="width:65%;"></span>{% endif %}</p>
      </div>
      {% if image.website %}
        </a>
      {% endif %}
    </div>
  </div>
  {% endfor %}
</div>

<br>



<div class="row">
  <p><strong><pre class="tab" style="font-size:2em"><font face="helvetica"> Released GERMS </font></pre></strong></p>
   <p>Jinlyung Choi, PhD</p>
<p>Phil Colgan, PhD</p>
<p>Chad Dolphin, MS</p>
<p>Shane Dooley, PhD</p>
<p>Kate Glanville, PhD</p>
<p>Hannah Guyer, MS</p>
  <p>Weiquan Luo, MS </p>
  <p>Lanying Ma, PhD </p>
  <p>Nicole Ricker, PhD</p>
  <p>Liz Luby Rieke, PhD</p>
  <p>Abby Schaefer, MS</p>
  <p>Schuyler Smith, PhD</p>
  <p>Thanwalee "JiJY" Sooksa-Nguan, PhD </p>
  <p>Ryan Williams, PhD </p>
  <p>Fan Yang, PhD</p>
</div>
<div class="row">
  <p><strong><pre class="tab" style="font-size:2em"><font face="helvetica"> Past Visiting GERMS </font></pre></strong></p>
  <p>Fernando Igne Rocha, Universidade Federal Rural do Rio de Janeiro</p>
<p>Ederson Jesus, Embrapa</p>
<p>Tomas Vetrovsky, Czech Academy of Sciences</p>
<p>Edward Lopatto, Grinnell College</p>
<p>Hyunji Yoo, Yonsei University</p>
<p>Minjoo Lee, Yonsei University</p>

 
</div>
