---
layout: page
title: Nantes FP
header: Nantes Functional Programming Group
---

All levels, all topics.
Mutable state prohibited.

## News

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>

