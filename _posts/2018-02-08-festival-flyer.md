---
layout: post
title:  "Festival Flyer"
img:    festival-flyer-front.jpg
alt:	Front of a flyer to advertise Festival Nr 6 in Portmeirion
gallery:
  - images/festival-flyer-back.jpg
---
A flyer to advertise Festival Nr 6 in Portmeirion.


The other side:
<div class="gallery">
	{% for img in page.gallery %}
	  	<img src="{{ site.baseurl }}/{{ img }}" alt="">
	{% endfor %}
</div>
