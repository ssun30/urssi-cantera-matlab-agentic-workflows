---
layout: page
title: Blog
permalink: /blog/
---

# Project blog

<ul class="post-list">
  {% for post in site.posts %}
  <li>
    <span class="post-meta">{{ post.date | date: "%B %-d, %Y" }}</span>
    <h3 style="margin-bottom:0.2em;">
      <a class="post-link" href="{{ post.url | relative_url }}">{{ post.title | escape }}</a>
    </h3>
    {% if post.subtitle %}<p style="margin-top:0;"><em>{{ post.subtitle | escape }}</em></p>{% endif %}
  </li>
  {% endfor %}
</ul>

{% if site.posts.size == 0 %}
*No posts yet — check back soon.*
{% endif %}
