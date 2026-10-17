---
layout: page
title: Now
---

## What I’m doing now

i'm in the 4th year of my PhD in biophysics at uc berkeley, working in the doudna lab. time flies. it feels like i came to berkeley yesterday after nomading for 2 years.

i'm always looking to meet introspective, curious, and kind people on my journey. if you know or are one of these, reach out at ronb - at - berkeley - dot - edu.

*This update was written Jul 10th, 2026.*

## Archives

{% assign updates = site.nowArchives | sort: 'date' | reverse %}
{% for update in updates %}
- [{{ update.date | date: "%B %-d, %Y" }}]({{ update.url | relative_url }})
{% endfor %}

[← back home]({{ '/' | relative_url }})
