---
layout: page
title: Books I've read
---

<!-- {% for bookPost in site.posts.booksread %}
  * {{ bookPost.date | date_to_string }} &raquo; [ {{ bookPost.title }} ]({{ bookPost.url }})
{% endfor %} -->

## Favorites

- Siddhartha, Demian - Herman Hesse
- The Alchemist - 
- The Power of Now - 
- Meditations - Marcus Aurelius
- Brave New World - Aldous Huxley

## Book notes

Below is a collection of notes on some of the books I've read. I have a strong preference for fiction novels, but rarely take notes on them. Short summary but detailed notes for each. This page will constantly update as I read more.

{% for project in site.data.books %}
   <a href="{{ project.url }}">{{ project.name }}</a> — {{ project.descr}}
{% endfor %}
