---
layout: page
title: Fotos
permalink: /fotos/
---

{% assign image_files = site.static_files | where: "photo", true %}
{% for img in image_files %}
  ![Trio]({{ img.path }}){: style="float: left"}
{% endfor %}