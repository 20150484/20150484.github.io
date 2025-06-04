---
layout: default
title: "Welcome"
---

# 👋 안녕하세요!
이 페이지는 Jekyll과 GitHub Pages를 활용한 나의 포트폴리오입니다.

아래는 최근 블로그 포스트입니다.

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a> - {{ post.date | date: "%Y-%m-%d" }}
    </li>
  {% endfor %}
</ul>

