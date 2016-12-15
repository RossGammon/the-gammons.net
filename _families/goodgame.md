---
title: Goodgame
layout: families
---

![Blue Lake, Mount Gambier]({{ site.baseurl }}/assets/images/BlueLakeMountGambier.jpg)

Blue Lake, Mount Gambier, South Australia

*My Goodgame Ancestry*
======================

So far, this branch of my family tree has been the hardest to research. This is due to several illegitimate children and many changes of name. So far I have traced the Goodgames back to the late 19th Century in South Australia.

This website starts with my Great Grandmother, Elsa Ruby (or Ruby May) Goodgame, who I think was born in 1899 at Mount Gambier, South Australia.

{% for goodgame in site.goodgame %}
  <div class="goodgame">
	<h4><a href="{{ goodgame.url }}">{{ goodgame.title }}</a></h4>
  </div>
{% endfor %}
