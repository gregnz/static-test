---
title: blog.homes.co.nz
layout: home
---

This is a test. It will conflict with my current local file.

This is the locally updated version

{% capture n  %}{{ site.posts | size | divided_by:3}}{% endcapture %}
{% capture m %} {{ n | times:2 }}{% endcapture %}
<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
      <p>{{ post.excerpt }}</p>
    </li>
  {% endfor %}
</ul>



