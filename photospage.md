---
layout: page
title:  "Homepage Photos!"
---

{% for photo in site.photos %}
  <h2>{{ photo.names }} - {{ photo.fileLocation }}</h2>
  <img src="{{site.baseurl}}/{{ photo.fileLocation }}">
  <p>{{ photo.content | markdownify }}</p>
{% endfor %}
