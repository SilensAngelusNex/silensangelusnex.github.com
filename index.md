---
layout: page
title: Welcome!
---
{% include JB/setup %}

[About](https://silensangelusnex.github.io/about)

## Roadrunner's Appalachian Trail Blog

<ul class="posts">
  {% for post in site.posts reversed %}
    <li><span>{{ post.date | date_to_long_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>

Make your own site like this with [Jekyll Bootstrap](http://jekyllbootstrap.com).
