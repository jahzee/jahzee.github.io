---
title: "Missing Morning Ebook"
excerpt: "Join Noe and Jeff as they solve the case of the missing morning. Narrated and illustrated by Jasmine." 
header:
  image: /assets/images/missingMorning/ebook/Cover.jpg
  teaser: /assets/images/missingMorning/ebook/Cover.jpg
---

{% include breadcrumbs.html %}

<style>
  .image-gallery {overflow: auto; margin-left: -1%!important;}
  .image-gallery a {float: left; display: block; margin: 0 0 1% 1%; width: 24%; text-align: center; text-decoration: none!important;}
  .image-gallery a span {display: block; text-overflow: ellipsis; overflow: hidden; white-space: nowrap; padding: 5px 5px;}
  .image-gallery iframe {
                 width:900px; height:675px;
                 border: 0;
                 -moz-transform: scale(0.70);
                 -moz-transform-origin: 0 0;
                 -o-transform: scale(0.70);
                 -o-transform-origin: 0 0;
                 -webkit-transform: scale(0.70);
                 -webkit-transform-origin: 0 0;
                 }
</style>

{% assign filenames="000,001,002,003,004,005,006,007,008,009,010,011,012,013,014" | split: "," %}

<div class ="image-gallery">
<br/>
{% for name in filenames %}
    <iframe src="{{ site.imagesurl}}{{"missingMorning/ebook/page"}}{{ name }}{{".xhtml"}}" scrolling="no"> </iframe>
{% endfor %}
<br>
</div>

{% include breadcrumbs.html %}

