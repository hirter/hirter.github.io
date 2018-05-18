---
title: Web
permalink: index.html
---
# Willkommen im Blog

<hr />
  {% for post in site.posts %}
      <a href="{{ post.url }}">{{ post.title }}</a> - {{post.date | date: "%B %e, %Y"}}<br />
      {{post.excerpt}}
      <hr />
  {% endfor %}
