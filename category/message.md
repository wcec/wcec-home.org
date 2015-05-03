---
layout: section 
title: 近期主日讲坛信息
permalink: /category/message/
---

近期主日讲坛信息
==================
<ul class="list-group">
 {% for post in site.categories['message'] offset: 0 limit: 8 %}
     <li class="list-group-item"> 
      {{post.date | date_to_string}}: {{ post.title }} {{ post.content }}
     </li>
 {% endfor %}
</ul>

----

更多讲道录音
--------------

 * [按照日期分类](/category/message-by-date/)
 * 按照讲员分类
 * 按照主题分类


