---
title: Web
permalink: index.html
---
# Willkommen im Blog

<hr />
<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a> - {{post.date | date: "%B %e, %Y"}}<br />
      {{post.excerpt}}
    </li>
  {% endfor %}
</ul>
