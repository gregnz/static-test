---
title: blog.homes.co.nz
layout: home
---
<div class="row">
  {% for post in site.posts %}
    <div class="col-md-4">
	<p>{{ post.excerpt }}</p>
	<a href="{{ post.url }}">{{ post.title }}</a>
    </div>
  {% endfor %}
</div>



