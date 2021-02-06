---
title: "Painting and Sculpture"
layout: collection
permalink: /painting-sculpture/
collection: painting-sculpture 
entries_layout: grid
classes: wide
---

{% include breadcrumbs.html %}

<style>
   .image-gallery {overflow: auto; margin-left: -1%!important;}
  .image-gallery a {float: left; display: block; margin: 0 0 1% 1%; width: 48%; text-align: center; text-decoration: none!important;}
  .image-gallery a span {display: block; text-overflow: ellipsis; overflow: hidden; white-space: nowrap; padding: 3px 0;}
  .image-gallery a img {width: 75%; display: block;}
</style>
  
{% assign filenames="p3.jpg,p2.jpg,p1.jpg,p4.jpg,p5.jpg,p6.jpg,p7.jpg,p8.jpg" | split: "," %}
 
<div class ="image-gallery">
<br>	
 {% for name in filenames %}
     <a href="{{ site.imagesurl }}{{"painting-sculpture/"}}{{ name }}">
	 <img src="{{site.imagesurl}}{{"painting-sculpture/"}}{{ name }} " alt="{{ name }}"/>
   	 <span>{{ filename }}</span>
    </a>
 {% endfor %}
<br>
</div>

{% include breadcrumbs.html %}

