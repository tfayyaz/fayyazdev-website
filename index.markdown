---
layout: default
---

# {{ site.title }}

{{ site.description }}

## Recent Posts

{% for post in site.posts limit:5 %}
  * [{{ post.title }}]({{ post.url | relative_url }}) - {{ post.date | date: "%B %d, %Y" }}
{% endfor %}

---

## About This Blog

This blog focuses on development, data visualization, and emerging technologies. I explore tools and techniques that help developers build better software and understand complex data.

[View all posts](/posts) | [About](/about)