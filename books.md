---
layout: page
title: Books
---

<!-- {% for bookPost in site.posts.booksread %}
  * {{ bookPost.date | date_to_string }} &raquo; [ {{ bookPost.title }} ]({{ bookPost.url }})
{% endfor %} -->

Below is a collection of notes on some books I've read - I began to heavily annotate books sometime during summer of 2017. I have a strong preference for reading fiction, but rarely take notes on them. Short summary but detailed notes for each. This page will constantly update as I read more.

## Favorites

- Siddhartha, Demian - Herman Hesse
- The Alchemist - 
- The Power of Now - 
- Meditations - Marcus Aurelius
- Brave New World - Aldous Huxley

## Book notes

Currently, no notes are posted. Stay tuned :)

{% for project in site.data.books %}
   <a href="{{ project.url }}">{{ project.name }}</a> — {{ project.descr}}
{% endfor %}
