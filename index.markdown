---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: default
title: Welcome to Teodorico's Blog
description: Introduction to DevSecOps
---

# Welcome to My DevSecOps Blog

This blog is dedicated to exploring DevSecOps principles and practices. Here you'll find posts about security, development, and operations integration.

## Recent Posts

{% for post in site.posts %}
* [{{ post.title }}]({{ post.url | relative_url }}) - {{ post.date | date: "%B %d, %Y" }}
{% endfor %}
