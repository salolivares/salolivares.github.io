---
layout: default
title: Archive
---

<ul class="posts">
  {% for post in site.categories.archives %}
  <li>
    <small class="datetime muted" data-time="{{ post.date }}">{{ post.date | date_to_string }} </small>
    <a href="{{ post.url }}">{{ post.title }}</a>
  </li>
  {% endfor %}
</ul>
