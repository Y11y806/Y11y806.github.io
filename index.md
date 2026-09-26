---
layout: home
title: 我的日常博客
---

# 文章列表
{% for post in site.posts %}
- {{ post.date | date: "%Y-%m-%d" }} 【{{ post.categories }}】 [{{ post.title }}]({{ post.url }})
{% endfor %}
