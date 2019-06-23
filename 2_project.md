---
layout: post-project
title: DU AN
description: MOT SO DU AN DA THAM GIA TRIEN KHAI.
image: assets/images/pic11.jpg
nav-menu: true
---
<section id="photos">
    {% for post in site.posts %}
		{% if post.image %}
		  <img src="{{site.baseurl}}/assets/images/thumbs/{{ post.title }}/{{ post.image }}" alt="{{post.title}}">		  
		{% endif %}
		<!-- <div class="container"> -->
			<!-- <h4>{{post.title}}</h4> -->
			<!-- <p>{{post.description}}</p> -->
		<!-- </div>    -->
   {% endfor %}
</div>

<script src="{{site.baseurl}}/js/photo-grid.js"></script>