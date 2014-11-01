---
layout: home
title: "Welcome"
homepage: true
ads: false
permalink: /
image:
  #feature: spider_portrait_1600x800.jpg
  feature: baffle.jpg
---

Hello and welcome to my webpage!  I'm a currently [Dicke postdoctoral fellow](http://www.princeton.edu/physics/about/employment/pfep/) in experimental physics at Princeton University.  On this page, you'll find details [about me](about), the [research I work on](/research), as well as the occasional [blog post](/blog).

#Recent blog posts
<div class="tiles">
{% for post in site.posts %}
	{% include post-grid.html %}
{% endfor %}
</div><!-- /.tiles -->
