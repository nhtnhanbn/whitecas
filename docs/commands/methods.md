---
sitemap: true
layout: default
title: Methods commands reference
---

## Commands reference

[All commands]({{ '/docs/commands' | relative_url }})

Commands relevant to Mathematical Methods in dictionary order. Documentation applicable for latest updates of commands.

{% for page in site.pages %}
  {% if page.layout == "command" and page.sm != true %}
[{{ page.slug }}]({{ page.url | relative_url }}) - {{ page.description }}
  {% endif %}
{% endfor %}