---
title: 首页
layout: page
feature_image: "https://picsum.photos/1300/400?image=989"
feature_text: |
  # 抵制自如甲醛房
---

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
      {{ post.excerpt }}
    </li>
  {% endfor %}
</ul>
