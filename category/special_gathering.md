---
layout: section 
title: 特别聚会
permalink: /category/special_gathering/
---

特别聚会
==================
<ul class="list-group">
 {% for post in site.categories['special_gathering'] offset: 0 limit: 8 %}
     <li class="list-group-item"> 
      {{post.date | date_to_string}}: {{ post.title }} {{ post.content }}
     </li>
 {% endfor %}
</ul>


