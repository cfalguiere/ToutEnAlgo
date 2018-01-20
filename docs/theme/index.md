---
layout: theme
title: Themes
date: '2017-12-27 10:30:00 CET'
tags: ['Theme']
published: true
assetsFolder: /ToutEnAlgo/assets/theme
---


<p>
  <ul class="tags">
    {% for tag in site.tags %}
      {% assign t = tag | first %}
      {% assign posts = tag | last %}
      {% assign tagName = t | downcase | replace:" ","-"  %}
      {% assign tagCount = posts | size  %}
      <li>{{ tagName }} : {{ tagCount }} posts</li>
    {% endfor %}
</ul>
</p>
