---
layout: page
title: Presentations
permalink: /presentations/
---

{% for pres in site.presentations %}
 * [{{pres.title}}]({{ pres.url }})
{% endfor %}
