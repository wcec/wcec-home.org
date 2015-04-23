---
layout: section
title:  甘霖
permalink: /ganlin/
---
<h1> 甘霖期刊 </h1>

 * <a href="{{site.media_url}}/doc/ganlin/GanLin_2015_poster.pdf">
        <img src="{{site.media_url}}/event/2015/20150615_ganlin.png"
        alt="GanLin poster" class="img-thumbnail thumbnail-size">
        甘霖期刊2015夏季刊征稿
   </a>
 
 * <a href="{{site.media_url}}/doc/ganlin/Ganlin_2015_01.pdf"> 
    <img src="{{site.media_url}}/doc/ganlin/ganlin_2015_1.png"
      class="img-thumbnail thumbnail-size">
    2015甘霖1月刊电子版 PDF下载 
  </a>

<ul class="list-group">

  <li class="list-group-item"> <a
  href="{{site.media_url}}/doc/ganlin/Ganlin_2014_06.pdf"> 2014甘霖6月刊电子版 PDF下载</a> </li>
  <li class="list-group-item"> <a
  href="{{site.media_url}}/doc/ganlin/Ganlin_2013_11.pdf"> 2013甘霖11月刊电子版 PDF下载</a> </li>
  <li class="list-group-item"> <a href="{{site.media_url}}/doc/ganlin/Ganlin_2013_03.pdf"> 2013甘霖3月刊电子版 PDF下载</a> </li>
  <li class="list-group-item"> <a
  href="{{site.media_url}}/doc/ganlin/Ganlin_2012_12.pdf"> 2012甘霖12月刊电子版 PDF下载</a> </li>
  <li class="list-group-item"> <a href="{{site.media_url}}/doc/ganlin/Ganlin_2012_09.pdf"> 2012甘霖9月刊电子版 PDF下载</a> </li>
  <li class="list-group-item"> <a href="{{site.media_url}}/doc/ganlin/Ganlin_2012_06.pdf"> 2012甘霖6月刊电子版 PDF下载</a> </li>
  <li class="list-group-item">
  <a href="{{site.media_url}}/doc/ganlin/Ganlin_2011part1.pdf"> 2011甘霖电子版 PART_1 下载</a> 
  <a href="{{site.media_url}}/doc/ganlin/Ganlin_2011part2.pdf"> 2011甘霖电子版 PART_2 下载</a> 
  </li>
  <li class="list-group-item"> <a href="{{site.media_url}}/doc/ganlin/Ganlin_2010.pdf"> 2010甘霖电子版 PDF下载</a> </li>
  <li class="list-group-item"> <a
  href="{{site.media_url}}/doc/ganlin/Ganlin_2009.pdf"> 2009甘霖电子版 PDF下载</a> </li>
</ul>

<hr/>
<ul class="list-group">
{% for post in site.categories['ganlin'] %}
    <li class="list-group-item"><a href="{{ post.url }}">{{ post.title }}</a></li>
{% endfor %}
</ul>
