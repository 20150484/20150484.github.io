---
layout: default
title: "Welcome"
---

# 👋 안녕하세요!

이곳은 제 블로그입니다.

- [소개](about.md)
- [프로젝트](projects.md)

## 최근 글 목록

<ul>
  {% for post in site.posts %}
    <li><a href="{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>

