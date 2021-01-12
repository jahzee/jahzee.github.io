---
title: "Diamond And Bird"
excerpt: "When a diamond is surrounded by so many people, what did his friend bird do to help?"
header:
  image: /assets/images/diamondAndBird/p9.jpg
  teaser: /assets/images/diamondAndBird/p9.jpg
---
{% include breadcrumbs.html %}

<style>
 .image-gallery {overflow: auto; margin-left: -1%!important;}
 .image-gallery a {float: left; display: block; margin: 0 0 1% 1%; width: 24%; text-align: center; text-decoration: none!important;}
 .image-gallery a span {display: block; text-overflow: ellipsis; overflow: hidden; white-space: nowrap; padding: 3px 0;}
 .image-gallery a img {width: 100%; display: block;}
</style>

{% assign filenames="p1.jpg,p2.jpg,p3.jpg,p4.jpg,p5.jpg,p6.jpg,p7.jpg,p8.jpg,p9.jpg,p10.jpg,p11.jpg,p12.jpg" | split: "," %}

<div class ="image-gallery">
<br>
{% for name in filenames %}
    <a href="{{ site.imagesurl}}{{"diamondAndBird/"}}{{ name }}">
      <img src="{{site.imagesurl}}{{"diamondAndBird/"}}{{ name }} " alt="{{ name }}"/> 
      <span>{{ filename }}</span>
     </a>
 {% endfor %}
<br>
</div>

<br>
{% include breadcrumbs.html %}

