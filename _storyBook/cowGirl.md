---
title: "Cow Girl"
excerpt: "Adventure story of a 4 year old girl in Paris, written by Ashley, illustrated by Jasmine" 
header:
  image: /assets/images/cowGirl/p0.jpg
  teaser: /assets/images/cowGirl/p0.jpg
---

{% include breadcrumbs.html %}

<style>
  .image-gallery {overflow: auto; margin-left: -1%!important;}
  .image-gallery a {float: left; display: block; margin: 0 0 1% 1%; width: 24%; text-align: center; text-decoration: none!important;}
  .image-gallery a span {display: block; text-overflow: ellipsis; overflow: hidden; white-space: nowrap; padding: 5px 5px;}
  .image-gallery a img {width: 100%; display: block;}
</style>

{% assign filenames="p0.jpg,p1.jpg,p2.jpg,p3.jpg,p4.jpg,p5.jpg,p6.jpg,p7.jpg,p8.jpg,p9.jpg,p10.jpg,p11.jpg,p12.jpg,p13.jpg,p14.jpg,p15.jpg,p16.jpg,p17.jpg,p18.jpg,p19.jpg,p20.jpg,p21.jpg" | split: "," %}

<div class ="image-gallery">
<br/>
{% for name in filenames %}
    <a href="{{ site.imagesurl}}{{"cowGirl/"}}{{ name }}" >
      <img src="{{site.imagesurl}}{{"cowGirl/"}}{{ name }} " alt="{{ name }}" /> 
    </a>
{% endfor %}
<br>
</div>

{% include breadcrumbs.html %}

