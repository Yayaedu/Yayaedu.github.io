---
layout: page
title: Forside
permalink: /
---

## Navigation
- [Blog (ugentligt)](/blog/)
- [Projekter](/projekter/)
- [Noter](/noter/)
- [Eksperimenter](/eksperimenter/)
- [Refleksioner](/refleksioner/)
- [Læringsmål & læringsplan](/laeringsmaal/)

## Formål
Her dokumenterer jeg løbende mit arbejde gennem semestret – inkl. skitser, noter, eksperimenter og færdige/ufærdige produkter.

## Seneste blogindlæg
<ul>
{% for post in site.posts limit:5 %}
  <li><a href="{{ post.url }}">{{ post.title }}</a> – {{ post.date | date: "%d-%m-%Y" }}</li>
{% endfor %}
</ul>
