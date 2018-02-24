---
title: My page
permalink: index.html
---
# Header 1
## Header 2
### Header 3

- Bulleted
- List

posts:
<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a> - {{post.date}}<br />
      {{post.excerpt}}
    </li>
  {% endfor %}
</ul>
