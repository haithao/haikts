---
layout: post
title: TU VAN
description: GOC CHUYEN GIA TU VAN.
image: assets/images/pic07.jpg
nav-menu: true
---

<!-- All post -->

<div class="inner">
{% for post in site.posts %}
{% if post.type == 'tuvan' %}
{% if post.title != 404 %}
	<p>
	<a href="{{site.baseurl}}{{post.url}}" class="portfolio-box">
		<h2>{{ post.title }}</h2>
	</a>
	<!-- {% if post.image %}<span class="image main"><img src="{{ site.baseurl }}/{{ post.image }}" alt="" /></span>{% endif %} -->
	<br>{% if post.date %} {{ post.date }} {% endif %}
	<br><h3>{{ post.description }}</h3>
	</p>
{% endif %}
{% endif %}
{% endfor %}
</div>
