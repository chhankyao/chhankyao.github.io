---
title: "Chun-Han (Hank) Yao - Home"
layout: gridlay
excerpt: "Chun-Han Yao"
sitemap: false
permalink: /
---

<div class="container-fluid">

<div class="row">

<div class="col-sm-7" style="text-align:justify">    
    
I am a Research Scientist at Stability AI, focusing on 3D/4D generation tasks. Prior to this, I was a PhD student in the Vision and Learning Lab at UC Merced, supervised by professor [Ming-Hsuan Yang](http://faculty.ucmerced.edu/mhyang/). During my PhD, I was honored to work with [Tony Tung](https://sites.google.com/site/tony2ng/) and [Nikolaos Sarafianos](https://nsarafianos.github.io/) at Meta, [Varun Jampani](https://varunjampani.github.io/) and [Boqing Gong](http://boqinggong.info/) at Google, [Jimei Yang](https://jimeiyang.github.io/) at Adobe, and [Chen Fang](http://fangchen.org/) at ByteDance. Before my PhD, I received my MS in Computer Science from UC San Diego and BS in Electrical Engineering from National Taiwan University (NTU). 
    
My research interests include weakly-supervised or unsupervised learning for video and 3D computer vision. My past experience spans the fields of video temporal consistency, object detection, domain adaptation, federated learning, as well as monocular 3D reconstruction of rigid objects, articulated shapes, and human bodies.

**_If you are interested in research collaboration, feel free to drop me an email with your CV._**

</div>

    
<div class="col-sm-4" style="display:table-cell; vertical-align:middle; text-align:left">

  <ul style="overflow: hidden">
  <img src="{{ site.url }}{{ site.baseurl }}/images/profile_photo.jpg" class="img-responsive" width="100%" />
  </ul>

  <!-- <br clear="all" /> -->

  <A HREF="">cyao6 [at] ucmerced [dot] com</A> <br>
  Click <a href="../cv_chunhan.pdf"> here </a> for my CV.
  
</div>
</div>
</div>



<div class="col-sm-12">

### Publications
  
Check my <a href="https://scholar.google.com/citations?hl=en&user=866vORgAAAAJ"> Google Scholar </a> page for more up-to-date publications.

{% for publi in site.data.publist limit:30 %}

<div class="col-sm-11 clearfix">
 <div class="well">
 <pubtit>{{ publi.title }}</pubtit>

 <p><em>{{ publi.authors }}</em></p>

 <p>{{ publi.venue }}</p>

 {% if publi.number_link == 1 %}
 <p><a href="{{ publi.link1.url }}">{{ publi.link1.display }}</a></p>
 {% endif %}

 {% if publi.number_link == 2 %}
 <p><a href="{{ publi.link1.url }}">{{ publi.link1.display }}</a>
 /
 <a href="{{ publi.link2.url }}">{{ publi.link2.display }}</a></p>
 {% endif %}

 {% if publi.number_link == 3 %}
 <p><a href="{{ publi.link1.url }}">{{ publi.link1.display }}</a>
 /
 <a href="{{ publi.link2.url }}">{{ publi.link2.display }}</a>
 /
 <a href="{{ publi.link3.url }}">{{ publi.link3.display }}</a></p>
 {% endif %}

 {% if publi.number_link == 4 %}
 <p><a href="{{ publi.link1.url }}">{{ publi.link1.display }}</a>
 /
 <a href="{{ publi.link2.url }}">{{ publi.link2.display }}</a>
 /
 <a href="{{ publi.link3.url }}">{{ publi.link3.display }}</a>
 /
 <a href="{{ publi.link4.url }}">{{ publi.link4.display }}</a></p>
 {% endif %}

 {% if publi.number_link == 5 %}
 <p><a href="{{ publi.link1.url }}">{{ publi.link1.display }}</a>
 /
 <a href="{{ publi.link2.url }}">{{ publi.link2.display }}</a>
 /
 <a href="{{ publi.link3.url }}">{{ publi.link3.display }}</a>
 /
 <a href="{{ publi.link4.url }}">{{ publi.link4.display }}</a>
 /
 <a href="{{ publi.link5.url }}">{{ publi.link5.display }}</a></p>
 {% endif %}

 </div>
</div>

{% endfor %}

<br clear="all"/>

#### <a href="{{ site.url }}{{ site.baseurl }}/publications">see all publications</a>

</div>
