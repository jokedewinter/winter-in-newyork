---
layout: post
title:  "Lissitzky poster"
img:    lissitzky-01.jpg
alt:	Poster for a Lissitzky exhibition.
gallery:
  - briefs/lissitzky/lissitzky-02.jpg
  - briefs/lissitzky/lissitzky-03.jpg
  - briefs/lissitzky/lissitzky-04.jpg
---
Poster for an exhibition featuring El Lissitzky. I tried to replicate Lissitzky's style (we were not allowed to use real art images), but I am not sure I have captured it quite how I wanted it.

Other versions:
<div class="gallery">
	{% for img in page.gallery %}
	  	<img src="{{ site.baseurl }}/{{ img }}" alt="">
	{% endfor %}
</div>
