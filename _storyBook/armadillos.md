---
title: "All About Armadillos"
excerpt: "Jasmine would lead you through facinating facts about Armadillos"
header:
  image: /assets/images/armadillos/p_000001.jpg
  teaser: /assets/images/armadillos/p_000001.jpg
---

{% include breadcrumbs.html %}

<style>
 .image-gallery {overflow: auto; margin-left: -1%!important;}
 .image-gallery a {float: left; display: block; margin: 0 0 1% 1%; width: 24%; text-align: center; text-decoration: none!important;}
 .image-gallery a span {display: block; text-overflow: ellipsis; overflow: hidden; white-space: nowrap; padding: 3px 0;}
 .image-gallery a img {width: 100%; display: block;}
</style>

{% assign filenames="p_000001.jpg,p_000002.jpg,p_000003.jpg,p_000004.jpg,p_000005.jpg,p_000006.jpg,p_000007.jpg,p_000008.jpg,p_000009.jpg,p_000010.jpg,p_000011.jpg,p_000012.jpg,p_000013.jpg,p_000014.jpg,p_000015.jpg,p_000016.jpg,p_000017.jpg,p_000018.jpg,p_000019.jpg,p_000025.jpg" | split: "," %}

<div class ="image-gallery">
<br>
{% for name in filenames %}
    <a href="{{ site.imagesurl}}{{"armadillos/"}}{{ name }}">
      <img src="{{site.imagesurl}}{{"armadillos/"}}{{ name }} " alt="{{ name }}"/> 
      <span>{{ filename }}</span>
     </a>
 {% endfor %}
<br>
</div>


{% include breadcrumbs.html %}
