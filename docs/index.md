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



<table>
  {% for post in site.posts %}
    <tr>
      <td>
          <img style="float:left;" src="{{ page.assetsFolder }}/images/blog/thumbmail-empty-150x150.png" href="{{ post.url | relative_url  }}" />
      </td>
      <td>
          {% for tag in page.tags %}
            <span style="background-color:#d22501;">{{ tag }}</span>&nbsp;
          {% endfor %}
          <br>
          <a href="{{ post.url | relative_url  }}">{{ post.title }}</a>
      </td>
    </tr>
  {% endfor %}
</table>


<!--
<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url | relative_url  }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>
-->
