---
layout: archive
title: '<span class="lang-es">Publicaciones</span><span class="lang-en">Publications</span>'
permalink: /publications/
author_profile: true
---

{% include base_path %}

<span class="lang-es">Lista de publicaciones indexadas.</span><span class="lang-en">Indexed publications list.</span>

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
