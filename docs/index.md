---
layout: landpage
title: Landpage
date: '2017-12-29 11:30:00 CET'
category: Landpage
published: true
assetsFolder: /ToutEnAlgo/assets/
---

<h1>
A la Une
</h1>

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url | relative_url  }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>

