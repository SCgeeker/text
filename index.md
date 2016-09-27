---
title: CSC Text
layout: page
---

<ul class="listing">
{% for post in site.posts %}
  <li class="listing-item">
    <a href="{{ site.url }}{{ post.url }}" title="{{ post.title }}">{{ post.title }}</a>
  </li>
{% endfor %}
</ul>

