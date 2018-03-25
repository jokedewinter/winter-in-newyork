---
layout: post
title:  "Athens mobile website"
img:    athens-mobile-01.jpg
alt:	Section of the Athens mobile website. 
gallery:
  - images/athens-mobile-02.jpg
  - images/athens-mobile-03.jpg
  - images/athens-mobile-04.jpg
  - images/athens-mobile-05.jpg
---
The mobile website for Athens. Broken up in pieces, because it's quite long.

<div class="gallery">
	{% for img in page.gallery %}
	  	<img src="{{ site.baseurl }}/{{ img }}" alt="">
	{% endfor %}
</div>
