---
title: "Pencil Sketches"
excerpt: "Selected Pencil Sketches"
header:
  image: /assets/images/miscSketches/p1.jpg
  teaser: /assets/images/miscSketches/p1.jpg
---

{% include breadcrumbs.html %}

<style>
   .image-gallery {overflow: auto; margin-left: -1%!important;}
  .image-gallery a {float: left; display: block; margin: 0 0 1% 1%; width: 49%; text-align: center; text-decoration: none!important;}
  .image-gallery a span {display: block; text-overflow: ellipsis; overflow: hidden; white-space: nowrap; padding: 3px 0;}
  .image-gallery a img {width: 100%; display: block;}
</style>
  
{% assign filenames="p1.jpg,p2.jpg,p3.jpg,p5.jpg,p4.jpg,p6.jpg,p7.jpg,p10.jpg,p9.jpg,p8.jpg,p11.jpg" | split: "," %}
 
<div class ="image-gallery">
<br>	
 {% for name in filenames %}
     <a href="{{ site.imagesurl }}{{"miscSketches/"}}{{ name }}">
	 <img src="{{site.imagesurl}}{{"miscSketches/"}}{{ name }} " alt="{{ name }}"/>
    </a>
 {% endfor %}
<br>
</div>

{% include breadcrumbs.html %}

