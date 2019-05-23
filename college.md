---
layout: single
title: College
permalink: /college/
author_profile: true
---

<ul>
  {% for post in site.college %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>