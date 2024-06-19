---
layout: page
title: Portofolio
excerpt: "My ventures, investments and initiatives"
search_omit: true
---

<ul class="post-list">
{% for post in site.categories.portofolio %}
  <li><article><a href="{{ site.url }}{{ post.url }}">{{ post.title }} <span class="entry-date"><time datetime="{{ post.date | date_to_xmlschema }}">{{ post.date | date: "%B %d, %Y" }}</time></span>{% if post.excerpt %} <span class="excerpt">{{ post.excerpt }}</span>{% endif %}</a></article></li>
{% endfor %}
</ul>
