---
layout: page
title: particpants
---

{% for participant in site.data.participants %}
- {{ participant.firstname }} {{ participant.lastname }}
{% endfor %}

