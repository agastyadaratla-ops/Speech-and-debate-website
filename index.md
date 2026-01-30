
---
layout: default
title: Announcements
---

{% for post in site.posts %}
<h2>{{ post.title }}</h2>
{{ post.content }}
<hr>
{% endfor %}
