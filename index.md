---
title: My page
permalink: index.html
---
# Header 1
## Header 2
### Header 3

- Bulleted
- List

{% for post in site.categories[page.category] %}
    <a href="{{ post.url | absolute_url }}">
      {{ post.title }}
    </a>
{% endfor %}
