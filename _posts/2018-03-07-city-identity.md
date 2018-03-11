---
layout: post
title:  "City identity for Athens"
img:    athens-logo.jpg
alt:	Logo concept for the city of Athens in Greece.
gallery:
  - images/athens-style.jpg
---
An identity for the city of Athens. The concept is "Meet the modern Greeks". Some of the icons used are typical of Ancient Greece, and the others are referring to Athens as a modern city with modern architecture and lots of streets with stairs and sport.

<div class="gallery">
	{% for img in page.gallery %}
	  	<img src="{{ site.baseurl }}/{{ img }}" alt="">
	{% endfor %}
</div>
