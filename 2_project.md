---
layout: post-project
title: DU AN
description: MOT SO DU AN DA THAM GIA TRIEN KHAI.
image: assets/images/pic11.jpg
nav-menu: true
---
<div id="container">
<div id="grid" data-columns class="cols">
    {% for post in site.posts %}
    <div class="box" style="background-color:#{{post.color}}">
       {% if post.image %}
          <img class="feat-image" src="{{site.baseurl}}/assets/images/thumbs/{{ post.title }}/{{ post.image }}" alt="{{post.title}}">		  
       {% endif %}
          <div class="container">
            <h4>{{post.title}}</h4>
            <p>{{post.description}}</p>
             <!-- <div class="action">{{ post.date | date: '%B %d, %Y' }}<a href="{{post.url | prepend: site.baseurl}}"><i class="fa fa-arrow-right" aria-hidden="true"></i></a></div>  -->
        </div>   
    </div>
   {% endfor %}

</div>
</div>

<script src="{{site.baseurl}}/js/salvattore.min.js"></script>