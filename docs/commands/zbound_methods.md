---
latex: true
layout: bound
title: Bound Reference
---

{% for doc in site.pages %}
  {% if doc.layout == "command" and doc.commandtype != "eActivity" and doc.sm != true %}

<div style="break-inside: avoid" markdown="1">

## {{ doc.slug }} ({{ doc.commandtype }})

Command last updated {{ doc.update }}.

{{ doc.content }}

</div>

  {% endif %}
{% endfor %}
