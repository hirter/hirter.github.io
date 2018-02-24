---
title: Web
permalink: index.html
---
# Willkommen im Blog

<hr />
<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a> - {{post.date}}<br />
      {{post.excerpt}}
    </li>
  {% endfor %}
</ul>
