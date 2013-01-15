---
layout: 2col
title: "Hackathons"
header: "Hackathons"
group: navigation
comments: false
---

## What is a hackathon?

Hackathons are events where participants have a short time period, usually a day or two, to build something cool.

## Past hackathons

{% for item in site.categories.hackathon %}
- [{{ item.title }}]({{ item.url }}){% endfor %}