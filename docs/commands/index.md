---
sitemap: true
layout: default
title: Commands reference
---

## Commands reference

[Commands relevant to Mathematical Methods]({{ '/docs/commands/methods' | relative_url }})

[Commands relevant to only Specialist Mathematics]({{ '/docs/commands/specialist' | relative_url }})

More commands available at [Casio Solutions](https://charliewatson.com/casio/cpintro.php)

All commands in dictionary order. Documentation applicable for latest updates of commands.

{% for page in site.pages %}
  {% if page.layout == "command" %}
[{{ page.slug }}]({{ page.url | relative_url }}) - {{ page.description }}
  {% endif %}
{% endfor %}
