---
layout: archive
title: "信息可视化心得"
date: 2018-1-1T14:25:45-04:00
modified:
excerpt: "小小总结"
tags: []
image: 
  feature: infovisnotes.jpg
  teaser:
---


<div class="tiles">
{% for post in site.categories.infovisnotes %}
  {% include post-grid.html %}
{% endfor %}
</div><!-- /.tiles 把所有categories 有 infovisnotes 的列出来-->
