---
title: "Drawings from Daily Note Book"
layout: collection
permalink: /notebook/
collection: notebook 
entries_layout: grid
classes: wide
---

{% include breadcrumbs.html %}

<style>
   .image-gallery {overflow: auto; margin-left: -1%!important;}
  .image-gallery a {float: left; display: block; margin: 0 0 1% 1%; width: 22%; text-align: center; text-decoration: none!important;}
  .image-gallery a span {display: block; text-overflow: ellipsis; overflow: hidden; white-space: nowrap; padding: 3px 0;}
  .image-gallery a img {width: 75%; display: block;}
</style>
  
 
<div class ="image-gallery">
<br>	
 {% for image in site.static_files%}
  {% if image.path contains '/assets/images/notebook/' %}
     <a href="{{image.path}}">
	 <img src="{{image.path}} " alt="{{ image.path}}"/>
    </a>
  {% endif %}
 {% endfor %}
<br>
</div>

{% include breadcrumbs.html %}

