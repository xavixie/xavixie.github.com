---
layout: page
title: Blog
tagline: index
---
{% include JB/setup %}

<h2>All Posts</h2>

<ul class="posts">
  {% for post in site.posts %}
   <!--  <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li> -->
   <li><span> <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>



