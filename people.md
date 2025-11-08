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

  - image_path:  /photos-team/bolivar.jpg
    title:  Bolivar Aponte Rolon, PhD
    position:  Postdoc

  - image_path: /photos-team/grace.jpg
    title:  Grace Carey 
    position:  PhD Candidate (Micro)

  - image_path: /photos-team/lillian.jpg
    title:  Lillian Chiang
    position:  MS Student (Env Sci)
    
  - image_path: /photos-team/phillip_headshot.jpeg
    title:  Phillip de Lorimier
    position:  PhD Student (Env Sci)
    
  - image_path: /photos-team/Nicole_headshot.jpg
    title:  Nicole Geerdes
    position:  PhD Student (EnvSci)

  - image_path: /photos-team/sakib.jpg
    title:  Najmuj Sakib (Sakib)
    position:  PhD Student (Micro)

  - image_path: /photos-team/clarisse.jpg
    title:  Clarisse Siababa
    position:  PhD Student (Micro)
    
  - image_path: /photos-team/Morgan_photo.jpg
    title: Morgan Lang
    position:  Undergraduate RA

  - image_path: /photos-team/Brenna_photo.jpg
    title: Brenna Halsted
    position:  Undergraduate RA
 
  - image_path: /photos-team/Ryan_photo.jpeg
    title: Ryan Donaldson
    position:  Undergraduate RA
 
  - image_path: /photos-team/Joy_photo.jpeg
    title: Joy Do
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
  <p>Laura Alt, PhD</p> 
  <p>Puja Bajracharya</p>
  <p>Jinlyung Choi, PhD</p>
<p>Phil Colgan, PhD</p>
<p>Chad Dolphin, MS</p>
<p>Shane Dooley, PhD</p>
<p>Jared Flater, PhD</p>
<p>Kate Glanville, PhD</p>
<p>Hannah Guyer, MS</p>
  <p>Juliana Johnson</p>
  <p>Jia Liu, PhD </p>
  <p>Weiquan Luo, MS </p>
  <p>Lanying Ma, PhD </p>
  <p>Michael Millican, PhD </p>
  <p>Nicole Ricker, PhD</p>
  <p>Liz Luby Rieke, PhD</p>
  <p>Abby Schaefer, MS</p>
  <p>Schuyler Smith, PhD</p>
  <p>Thanwalee "JiJY" Sooksa-Nguan, PhD </p>
  <p>Paul Villanueva, PhD </p>
  <p>Ryan Williams, PhD </p>
  <p>Fan Yang, PhD</p>
  <p>Jihoon Yang, PhD</p>
  <p>Kaija Dahlberg</p>
  <p>Lily Haas</p>
  <p>Emma Nieland</p>
  <p>Erik Raman </p>

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
