---
sitemap: true
layout: default
title: Specialist commands reference
---

## Commands reference

[See also commands relevant to both Mathematical Methods and Specialist Mathematics]({{ '/docs/commands/methods' | relative_url }})

[All commands]({{ '/docs/commands' | relative_url }})

Commands relevant to only Specialist Mathematics. Documentation applicable for latest updates of commands. [Changelog]({{ '/docs/changelog' | relative_url }})

{% for page in site.pages %}
  {% if page.layout == "command" and page.sm == true %}
[{{ page.slug }}]({{ page.url | relative_url }}) - {{ page.description }}
  {% endif %}
{% endfor %}
