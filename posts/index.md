---
layout: page
title: 文章
permalink: /posts/
---

## 网页设计笔记：

{% for post in site.categories.rwd %}-  
	<a class="page-link" href="{{ site.url }}{{ post.url }}">{{ post.title }}</a><br>{{ post.description }}<br><br>
{% endfor %}
 

---

## 信息可视化笔记：

{% for post in site.categories.infovis %}- 
	<a class="page-link" href="{{ site.url }}{{ post.url }}">{{ post.title }}</a><br>{{ post.description }}<br><br>
{% endfor %}


