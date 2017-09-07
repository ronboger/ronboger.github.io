---
layout: page
title: Books
---

## Books Read

<!-- {% for bookPost in site.posts.booksread %}
  * {{ bookPost.date | date_to_string }} &raquo; [ {{ bookPost.title }} ]({{ bookPost.url }})
{% endfor %} -->


{% for project in site.data.books %}
   <a href="{{ project.url }}">{{ project.name }}</a> — {{ project.descr}}
{% endfor %}
