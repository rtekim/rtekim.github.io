---
layout: page
title:  "Homepage Photos!"
---

{% for photo in site.photos %}
  <h2>{{ staff_member.names }} - {{ staff_member.fileLocation }}</h2>
  <p>{{ staff_member.content | markdownify }}</p>
{% endfor %}
