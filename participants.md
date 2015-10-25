---
layout: page
title: Participants
banner: DSC013361.jpeg
---

{% for participant in site.data.participants %}
- {{ participant.firstname }} {{ participant.lastname }}
{% endfor %}

