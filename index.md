---
layout: index
title: Hack Northwestern
tagline: fostering student creativity, entrepreneurship, and hacker spirit
comments: false
tags: false
archive: false
---

## Upcoming Events

---
 
{% for item in site.categories.hack-night %}{% if item.date > site.time %}
- [{{ item.title }}]({{ item.link }}){% endif %}{% endfor %}