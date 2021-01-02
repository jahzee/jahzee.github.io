---
title: "Diamond And Bird"
excerpt: "When a diamond is surrounded by so many people, what did his friend bird do to help?"
header:
  image: /assets/images/diamondAndBird/p_000001.jpg
  teaser: /assets/images/diamondAndBird/p_000001.jpg
---
{% include breadcrumbs.html %}

<style>
 .image-gallery {overflow: auto; margin-left: -1%!important;}
 .image-gallery a {float: left; display: block; margin: 0 0 1% 1%; width: 32%; text-align: center; text-decoration: none!important;}
 .image-gallery a span {display: block; text-overflow: ellipsis; overflow: hidden; white-space: nowrap; padding: 3px 0;}
 .image-gallery a img {width: 100%; display: block;}
</style>

{% assign filenames="p_000002.jpg,p_000003.jpg,p_000004.jpg" | split: "," %}

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

