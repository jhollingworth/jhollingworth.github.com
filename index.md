---
layout: page
title: jhollingworth.com
supporting_tagline: ''
---
{% include JB/setup %}


{% for post in site.posts %}
  <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
{% endfor %}


