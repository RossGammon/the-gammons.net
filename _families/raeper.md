---
title: Raeper
layout: families
---

![Castle St. Turriff 1943]({{ site.baseurl }}/assets/images/castle_st_turriff_1943.jpg)

Photo of Castle Street, Turriff, Scotland 1943

*My Scottish Raeper Ancestry*
=============================

So far, my Raeper ancestry has been traced back to the early 19th Century in Banffshire, Scotland.

This website starts with my Great Grandfather, Alexander Raeper who was born in 1869 at Marnoch, Banffshire, Scotland.

{% for raeper in site.raeper %}
  <div class="raeper">
	<h4><a href="{{ raeper.url }}">{{ raeper.title }}</a></h4>
  </div>
{% endfor %}
