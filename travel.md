---
layout: single
title: Travel
permalink: /travel/
author_profile: true
---

<ul>
  {% for post in site.travels %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>