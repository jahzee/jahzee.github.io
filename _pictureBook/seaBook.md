---
title: "SeaBook"
excerpt: "Squid, clam, seahorse, and others from sea"
header:
  image: /assets/images/seaBook/p_000001.jpg
  teaser: /assets/images/seaBook/p_000001.jpg
---
<style>
 .image-gallery {overflow: auto; margin-left: -1%!important;}
 .image-gallery a {float: left; display: block; margin: 0 0 1% 1%; width: 32%; text-align: center; text-decoration: none!important;}
 .image-gallery a span {display: block; text-overflow: ellipsis; overflow: hidden; white-space: nowrap; padding: 3px 0;}
 .image-gallery a img {width: 100%; display: block;}
</style>

{% include breadcrumbs.html %}

{% assign filenames="p_000001.jpg,p_000002.jpg,p_000003.jpg,p_000004.jpg,p_000005.jpg,p_000006.jpg,p_000007.jpg,p_000008.jpg,p_000009.jpg" | split: "," %}

<div class ="image-gallery">
<br>
{% for name in filenames %}
    <a href="{{ site.imagesurl}}{{"seaBook/"}}{{ name }}">
      <img src="{{site.imagesurl}}{{"seaBook/"}}{{ name }} " alt="{{ name }}"/> 
     </a>
 {% endfor %}
<br>
</div>


{% include breadcrumbs.html %}
