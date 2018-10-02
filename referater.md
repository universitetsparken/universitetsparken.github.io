---
layout: page
title: Referater
permalink: /referater/
---

Referater fra generalforsamlinger.

<div class="ref-list">
<ul>
{% for pdf in site.static_files %}
  {% if pdf.path contains '/dokumenter/referater/' %}
    <li><a href="{{ pdf.path | prepend: site.baseurl  }}">{{ pdf.basename | replace_first: '-', ': ' | replace: '-', ' '}}</a></li>
  {% endif %}
{% endfor %}
</ul>
</div>
