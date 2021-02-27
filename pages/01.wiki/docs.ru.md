---
title: wiki
taxonomy:
    category:
        - docs
---

{% if config.plugins.tagcloud.enabled %}
  <aside class="widget widget_meta">
    <h2 class="widget-title">{{'POPULAR TAGS'|t}}</h2>
    {% include 'partials/tagcloud.html.twig' %}
    </aside>
{% endif %}