---
layout: page
title: 信息可视化笔记
permalink: /posts/infovis/
---

{% for post in site.categories.infovis %}- 
	<a class="page-link" href="{{ site.url }}{{ post.url }}">{{ post.title }}</a><br>{{ post.description }}<br><br>
{% endfor %}
