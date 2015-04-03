---
layout: section
title:  活动 
permalink: /category/event/
---

<ul class="list-group">
{% for post in site.categories['event'] %}
    <li class="list-group-item"><a href="{{ post.url }}">{{ post.title }}</a></li>
{% endfor %}
</ul>
