---
layout: panos
title: Photo
permalink: /photo/
---

{% assign photopanos = site.data.panos %}
{% for pano in photopanos %}![]({{site.url}}/assets/panos/{{pano.file}} "{{pano.name}}"){% endfor %}
