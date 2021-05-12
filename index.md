---
layout: default
title: "Happy Jekylling!"
---

<link href='https://fonts.googleapis.com/css?family=Varela' rel='stylesheet' type='text/css'>
<div class="IntroSection"> 
<h1 class="typewriter-text">LIVE WITH CODE</h1>
<!-- <h1>LIVE WITH</h1>
<div class="glitch" data-text="CODE">CODE</div> -->
<h2>A journey that goes beyond syntax</h2>
</div>


<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
      <a href="http://www.google.com"> google</a>
    </li>
  {% endfor %}
</ul>

