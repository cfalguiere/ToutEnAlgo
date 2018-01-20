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
          <a href="{{ post.url | relative_url  }}" ><img style="float:left;" src="{{ page.assetsFolder }}/images/blog/thumbmail-empty-150x150.png"> </a>
      </td>
      <td>
        <center>
          {% for tag in post.tags %}
            <span style="background-color:#91a61d;font-style:italic;">&nbsp;&nbsp;{{ tag }}&nbsp;&nbsp;</span>&nbsp;&nbsp;
          {% endfor %}
          <br>
          <a href="{{ post.url | relative_url  }}">{{ post.title }}</a>
        </center>
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
