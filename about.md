---
layout: default 
title: About
---

## Description
{{ site.description }}

 The following are some books I've read :
 {% for book in site.books %}
 - {{ book.title }}, author: {{ book.author }}
 {% endfor %}

