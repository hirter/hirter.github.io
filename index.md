---
title: Web
permalink: index.html
---
# Header 1
Willkommen im Blog
posts:
<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a> - {{post.date}}<br />
      {{post.excerpt}}
    </li>
  {% endfor %}
</ul>
