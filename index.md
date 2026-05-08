---
layout: default
title: 首页
---

# 欢迎来到我的博客

这里是首页内容，你可以写自我介绍、博客简介等。

## 最新文章

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
      - {{ post.date | date: "%Y-%m-%d" }}
    </li>
  {% endfor %}
</ul>
