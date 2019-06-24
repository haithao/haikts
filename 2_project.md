---
layout: post-project
title: DU AN
description: MOT SO DU AN DA THAM GIA TRIEN KHAI.
image: assets/images/pic11.jpg
nav-menu: true
---
<section id="photos">
<div class="row-no-gutters">
    {% for post in site.posts %}
		{% if post.image %}
		<a href="{{site.baseurl}}{{post.url}}" class="portfolio-box">
		  <img src="{{site.baseurl}}/assets/images/thumbs/{{ post.title }}/{{ post.image }}" alt="{{post.title}}">	
		</a>
		<div class="container">
			<!-- <h4>{{post.title}}</h4> -->
			{{post.description}}
		</div>
		{% endif %}  
   {% endfor %}
</div>
</div>

<script src="{{site.baseurl}}/js/photo-grid.js"></script>