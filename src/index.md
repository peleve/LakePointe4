---
layout: base
---

# Hello from Eleventy

This is a simple Eleventy demo

My sample Eleventy website after adding the front matter.

{% for post in collections.posts %}
- [{{ post.data.title }}, {{post.data.postdate}}]({{ post.url }})
{% endfor %}