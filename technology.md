---
layout: page
permalink: /tech/
title: Tech
---

 
{% for post in site.categories.technology %}
 <li><span>{{ post.date | date_to_string }}</span> &nbsp; <a href="{{ post.url }}">{{ post.title }}</a></li>
{% endfor %}