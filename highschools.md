---
layout: page
title: Phổ Thông
permalink: /highschools/
---


{% for post in highschools %}
    <li><a href="{{ post.url }}">{{ post.title }}</a></li>
{% endfor %}