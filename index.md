---
title: 홈
---

안녕하세요, 제가 모은 자료들을 정리하는 공간입니다.

## 글 목록

{% for post in site.posts %}
- [{{ post.title }}]({{ post.url | relative_url }}) — {{ post.date | date: "%Y-%m-%d" }}
{% endfor %}
