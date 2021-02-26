---
layout: defaults/page
permalink: index.html
narrow: true
title: POPGEN 연구실습
---

## 환영합니다!

{% include components/intro.md %}

<hr />

### Recent Posts

{% for post in site.posts limit:3 %}
{% include components/post-card.html %}
{% endfor %}


