---
title: Portfolio 
layout: collection
permalink: /portfolio/
collection: portfolio 
entries_layout: grid
classes: wide

galleries:
  - title: Jasmine's Sketch Collection
    image: /assets/images/animalSketches/p1.jpg
    url: /sketches/
  - title: Jasmine's Picture Book Collection
    image: /assets/images/robotBook/p_000001.jpg
    url: /pictureBook/
  - title: Jasmine's Colored Paint Collection
    image: /assets/images/self-portrait/jasmine_blue.jpg
    url: /paintBook/
  - title: Jasmine's Story Book Collection
    image: /assets/images/cowGirl/p0.jpg
    url: /storyBook/

---

{% if page.galleries %}{% include image-gallery-index.html %}{% endif %}


