---
title: blog.homes.co.nz
layout: home
---

![img-main-1600px.jpg](/uploads/img-main-1600px.jpg)

<div class="row">
{% for post in site.posts %}
<div class="col-md-4">
<p>{{ post.excerpt }}</p>
<a href="{{ post.url }}">{{ post.title }}</a>
</div>
{% endfor %}
</div>