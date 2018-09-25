---
layout: default
title: Best Of
---

<ul class="posts">
  {% for post in site.bestof %}
  <li>
    <small class="datetime muted" data-time="{{ post.date }}"><i>Last Updated</i> &nbsp; {{ post.date | date: "%B %Y" }} </small>
    <a href="{{ post.url }}">{{ post.title }}</a>
  </li>
  {% endfor %}
</ul>
