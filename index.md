---
layout: page
title: Hello World!
tagline: Welcome to BH8UTO Blog
---
{% include JB/setup %}


Here's a posts list.

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>

