---
sitemap: true
layout: default
title: Methods commands reference
---

## Commands reference

[All commands]({{ '/docs/commands' | relative_url }})

Commands relevant to Mathematical Methods. Documentation applicable for latest updates of commands. [Changelog]({{ '/docs/changelog' | relative_url }})

{% for page in site.pages %}
  {% if page.layout == "command" and page.sm != true %}
[{{ page.slug }}]({{ page.url | relative_url }}) - {{ page.description }}
  {% endif %}
{% endfor %}
