---
layout: archive
title: "Sitemap"
permalink: /sitemap/
author_profile: true
---

{% include base_path %}

Every page and entry on this site. An [XML version]({{ base_path }}/sitemap.xml) is available for crawlers.

<h2>Pages</h2>
<ul>
{% for post in site.pages %}
  {% if post.title and post.sitemap != false %}
    <li><a href="{{ post.url | relative_url }}">{{ post.title }}</a></li>
  {% endif %}
{% endfor %}
</ul>

{% for collection in site.collections %}
  {% if collection.output %}
    <h2>{{ collection.label | capitalize }}</h2>
    <ul>
    {% for post in collection.docs %}
      <li><a href="{{ post.url | relative_url }}">{{ post.title }}</a></li>
    {% endfor %}
    </ul>
  {% endif %}
{% endfor %}
