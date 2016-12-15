---
title: Gammon
layout: families
---

![Berrynarbor]({{ site.baseurl }}/assets/images/Bessemer_Thatch_-_geograph.org.uk_-_446340.jpg)

This photo is of Berrynarbor (Thanks to Roger Gittins - CCA-SA 2.0)

*The Gammons of Berrynarbor, Devonshire, England*
===============================================

So far, my Gammon ancestry has been traced back to the late 18th Century in Berrynarbor, Devonshire, England.

This website starts with my Great Grandfather, Edwin Alfred Gammon who was born in 1861 at Ilfracombe, Devonshire, England.

{% for gammon in site.gammon %}
  <div class="gammon">
	<h4><a href="{{ gammon.url }}">{{ gammon.title }}</a></h4>
  </div>
{% endfor %}
