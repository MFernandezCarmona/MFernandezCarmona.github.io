---
layout: archive
title: '<span class="lang-es">Proyectos</span><span class="lang-en">Projects</span>'
permalink: /portfolio/
author_profile: true
---

{% include base_path %}

<span class="lang-es">Proyectos de investigación y transferencia en los que he participado.</span><span class="lang-en">Research and transfer projects I have taken part in.</span>

{% for post in site.portfolio reversed %}
  {% include archive-single.html %}
{% endfor %}
