---
layout: default
image: '/images/pages/circuit.jpg'
---

<h2> Welcome </h2>

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
      <a href="http://www.google.com"> google</a>
    </li>
  {% endfor %}
</ul>