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
	<div class="img_wrap">
		{% if post.image %}
		<a href="{{site.baseurl}}{{post.url}}" class="portfolio-box">
		  <img src="{{site.baseurl}}/assets/images/thumbs/{{ post.image }}" class="image" >	
		</a>
		<p class="img_description">{{post.description}}</p>
		{% endif %}
	</div>
   {% endfor %}
</div>
</div>

<!-- <script src="{{site.baseurl}}/js/photo-grid.js"></script> -->
<script>
function getRandomSize(min, max) {
  return Math.round(Math.random() * (max - min) + min);
}
</script>

<!-- <style> -->
<!-- /* Show text */ -->
<!-- .img_wrap { -->
  <!-- position: relative; -->
  <!-- height: auto; -->
  <!-- width: auto; -->
<!-- } -->
 
<!-- .img_description { -->
	<!-- position: absolute; -->
	<!-- top: 30; -->
	<!-- bottom: 0; -->
	<!-- left: 0; -->
	<!-- right: 0; -->
	<!-- color: #fff; -->
	<!-- visibility: hidden; -->
	<!-- opacity: 0; -->
	<!-- font-size: 25px; -->
	<!-- Text-align:center; -->
 
  <!-- /* transition effect. not necessary */ -->
  <!-- transition: opacity .2s, visibility .2s; -->
<!-- } -->
 
<!-- .img_wrap:hover .img_description { -->
  <!-- visibility: visible; -->
  <!-- opacity: 1; -->
<!-- } -->
<!-- .img_wrap:hover .img_description { -->
  <!-- visibility: visible; -->
  <!-- opacity: 1; -->
<!-- } -->

<!-- /* image fade */ -->
<!-- .img_wrap:hover .image { -->
  <!-- opacity: 0.3; -->
<!-- } -->

<!-- .img_wrap:hover .middle { -->
  <!-- opacity: 1; -->
<!-- } -->

<!-- .text { -->
  <!-- background-color: #4CAF50; -->
  <!-- color: white; -->
  <!-- font-size: 16px; -->
  <!-- padding: 16px 32px; -->
<!-- } -->
<!-- </style> -->