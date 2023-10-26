---
layout: page
title: Tools and data
permalink: /resources/
feature-img: "assets/img/pexels/computer.jpeg"
---
<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>
