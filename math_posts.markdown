---
layout: page
title:  Math Posts
---
<ul style="list-style-type:none;">
{% for post in site.math_posts %}
<h2>
  <li><a href="{{ post.url }}">{{ post.title }}</a></li>
</h2>
<p>{{ post.excerpt }}</p>
{% endfor %}
</ul>
