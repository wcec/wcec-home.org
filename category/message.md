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

 * 01/25/2015 吕允智牧师 以恩慈相待 
 * 01/18/2015 黄昭彦长老 主啊！我肯（愿） 
 * 01/11/2015 石翔长老 述说神的荣耀 
 * 01/04/2015 吕允智牧师 以謙卑束腰 


----

 * 按照讲员分类
 * 按照日期分类
 * 按照主题分类

----

