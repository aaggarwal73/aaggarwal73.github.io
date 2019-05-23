---
layout: single
title: Travel
permalink: /travel/
author_profile: true
---

<ul>
  {% for single in site.posts %}
    <li>
      <a href="{{ single.url }}">{{ single.title }}</a>
    </li>
  {% endfor %}
</ul>