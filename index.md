---
title: Web
permalink: index.html
layout: default
---

# Willkommen im Blog
{% for post in site.posts %}

{% endfor %}

<!--
  
    <p>
      <a href="{{ post.url }}">{{ post.title }}</a> - {{post.date | date: "%B %e, %Y"}}<br />
      {{post.excerpt}}
    </p>
 
-->
