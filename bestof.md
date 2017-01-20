---
layout: default
title: Best Of
---

<ul class="posts">
  {% for post in site.categories.bestof %}
  <li>
    <small class="datetime muted" data-time="{{ post.date }}">{{ post.date | date_to_string }} </small>
    <a href="{{ post.url }}">{{ post.title }}</a>
  </li>
  {% endfor %}
</ul>
