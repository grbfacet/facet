---
layout: default
title: All Published Papers
---

{% for apage in site.pages %}
{% if apage.pagetype == "published" %}
* [{{ apage.title }}]({{ apage.url }})
{% endif %}
{% endfor %}
