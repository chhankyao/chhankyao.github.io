---
title: "Chun-Han Yao - Home"
layout: gridlay
excerpt: "Chun-Han Yao"
sitemap: false
permalink: /
---

<div class="container-fluid">

<div class="row">

<div class="col-sm-8">    
    
I am a PhD student in the Vision and Learning Lab at UC Merced, supervised by professor [Ming-Hsuan Yang](http://faculty.ucmerced.edu/mhyang/). During my PhD, I have collaborated with [Varun Jampani](https://varunjampani.github.io/), [Boqing Gong](http://boqinggong.info/) at Google, [Jimei Yang](https://jimeiyang.github.io/) at Adobe, and [Fang Chen](http://fangchen.org/) at ByteDance. Prior to that, I receied my MS in Computer Science from UC San Diego and BS in Electrical Engineering from National Taiwan University (NTU). 
    
My research interests include weakly-supervised or unsupervised learning for video and 3D computer vision. My past experience spans the fields of video temporal consistency, object detection, domain adaptation, federated learning, as well as monocular 3D reconstruction of rigid objects, articulated shapes, and human bodies.

**_If you are interested in research collaboration, feel free to drop me an email with your CV._**

    
### News
{% for article in site.data.news limit:9 %}
{{ article.date }} :
<em>{{ article.headline }}</em>
{% endfor %}
<a href="{{ site.url }}{{ site.baseurl }}/allnews.html">see all news</a>

</div>

    
<div class="col-sm-4" style="display:table-cell; vertical-align:middle; text-align:left">

  <ul style="overflow: hidden">
  <img src="{{ site.url }}{{ site.baseurl }}/images/profile_photo.jpg" class="img-responsive" width="100%" />
  </ul>

  <!-- <br clear="all" /> -->

  <A HREF="">cyao6 [at] ucmerced [dot] com</A> <br>
  UC Merced <br>
  5200 Lake Rd<br>
  Merced, CA, USA.<br>

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

<!--  <img src="{{ site.url }}{{ site.baseurl }}/images/pubpic/{{ publi.image }}" class="img-responsive" width="200px" style="float: left" /> -->

<!--  <p>{{ publi.description }}</p> -->

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