---
layout: page
title: News
permalink: /news
---

# My news

My first post is [here](/news/first)

<ul>
  {% for post in site.posts %}
  <li><a href="{{ post.url }}" class="post-preview">{{ post.title }}</a></li>
  {% endfor %}
</ul>