---
layout: default
permalink: /people/
github: /\_photo_gallery/github.png
current_images: 
  - image_path: /photos-team/howe.jpg
    title: Adina Howe, PhD 
    position:  PI
    website: https://github.com/germs-lab
    
  - image_path: /photos-team/lee.jpg
    title:  Jaejin Lee, PhD
    position:  Research Scientist
    
  - image_path: /photos-team/flater.jpg
    title:  Jared Flater, PhD
    position:  Postdoc
  
  - image_path:  /photos-team/kate.jpg
    title:  Kate Glanville, PhD
    position:  Postdoc
    
  - image_path:  /photos-team/jijy.jpg
    title:  Thanwalee <q>JiJY</q><br> Sooksa-nguan, PhD
    position:  Postdoc
    
  - image_path: /photos-team/jihoon2.jpg
    title: Jihoon Yang, PhD
    position:  Postdoc

  - image_path: /photos-team/alt.jpg
    title:  Laura Alt
    position:  PhD Student

  - image_path: /photos-team/dooley2.gif
    title:  Shane Dooley
    position:  PhD Student
    website: https://github.com/skdooley

  - image_path: /photos-team/liu.jpg
    title:  Jia Liu
    position:  PhD Student
    website:  https://github.com/jialiu232

  - image_path: /photos-team/smith.jpg
    title:  Schuyler Smith
    position:  PhD Student
    website: https://schuyler-smith.github.io/

  - image_path: /photos-team/villanueva.jpg
    title:  Paul Villanueva
    position:  PhD Student
    website: https://github.com/pommevilla?tab=repositories

  - image_path: /photos-team/luo.jpg
    title: Weiquan Luo 
    position:  MS Student

  - image_path: /photos-team/abby.jpg
    title: Abby Schaefer
    position:  MS Student

  - image_path: /photos-team/fernando.jpg
    title: Fernando Igne Rocha
    position:  Visiting Scholar

  - image_path: /photos-team/erik.jpg
    title: Erik Raman
    position:  Undergraduate RA


past_images: 

  - image_path: /photos-team/choi.jpg
    title:  Jinlyung Choi, PhD
    website: https://github.com/metajinomics
    
  - image_path: /photos-team/colgan.jpg
    title:  Phil Colgan, PhD

  - image_path:  /photos-team/ma.jpg 
    title:  Lanying Ma, PhD


  - image_path:  /photos-team/ricker.jpg
    title:  Nicole Ricker, PhD
    position:  Postdoc
  
  - image_path:  /photos-team/liz_fish.jpg
    title:  Liz Luby Rieke, PhD

    
  - image_path:  /photos-team/ryan.jpg
    title:  Ryan Williams, PhD
 

  - image_path: /photos-team/yang.jpg
    title: Fan Yang, PhD
    website: https://github.com/fandemonium

  - image_path: /photos-team/dolphin.jpg
    title: Chad Dolphin
    

  - image_path: /photos-team/guyer.jpg
    title: Hannah Guyer
 
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
  <p><strong><pre class="tab" style="font-size:2em"><font face="helvetica">  Released GERMS </font></pre></strong></p>
  {% for image in page.past_images %}
  <div class="column">
    <div class="card">
      {% if image.website %}<a href="{{ image.website }}" target="_blank" style="text-decoration: none">{% endif %}
      <img src="{{ image.image_path | prepend: site.baseurl }}" alt="{{ image.title }}" style="width:100%">
      <div class="container">
        <p class="title2" style="padding-top: 10px; margin-bottom: 0px">{{ image.title }}</p>
        <p class="title" style="margin: 0 ;padding-bottom: 10px;">{{ image.position }}
        {% if image.website %}<span style="float:right; position: relative; top: -15%;"><img src="/photos-team/github.png" alt="{{ image.title }}" style="width:65%;"></span>{% endif %}</p>
      </div>
      {% if image.website %}
        </a>
      {% endif %}
    </div>
  </div>
  {% endfor %}
</div>


<div class="row">
  <p><strong><pre class="tab" style="font-size:2em"><font face="helvetica"> Past Visiting GERMS </font></pre></strong></p>
<p>Ederson Jesus, Embrapa</p>
<p>Tomas Vetrovsky, Czech Academy of Sciences</p>
<p>Edward Lopatto, Grinnell College</p>
<p>Hyunji Yoo, Yonsei University</p>
<p>Minjoo Lee, Yonsei University</p>

 
</div>
