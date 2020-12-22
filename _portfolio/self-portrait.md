---
title: "Self-Portrait"
excerpt: "Multi-Colored Pastel Self-Portrait"
header:
  image: /assets/images/self-portrait/jasmine_pink.jpg
  teaser: /assets/images/self-portrait/jasmine_pink.jpg
---

<style>
   .image-gallery {overflow: auto; margin-left: -1%!important;}
  .image-gallery a {float: left; display: block; margin: 0 0 1% 1%; width: 49%; text-align: center; text-decoration: none!important;}
  .image-gallery a span {display: block; text-overflow: ellipsis; overflow: hidden; white-space: nowrap; padding: 3px 0;}
  .image-gallery a img {width: 100%; display: block;}
</style>
  
{% assign filenames="jasmine_pink.jpg,jasmine_blue.jpg,jasmine_green.jpg,jasmine_yellow.jpg" | split: "," %}
 
<div class ="image-gallery">
 {% for name in filenames %}
     <a href="{{ site.imagesurl }}{{"self-portrait/"}}{{ name }}">
	 <img src="{{site.imagesurl}}{{"self-portrait/"}}{{ name }} " alt="{{ name }}"/>
   	 <span>{{ filename }}</span>
    </a>
 {% endfor %}
</div>

{% include gallery caption="Jasmine's self-portrait drawn in 3rd grade" %}
