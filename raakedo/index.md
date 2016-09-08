---
layout: page
title: Raakedo
excerpt: "Archives de mes articles de la chronique du Raakedo publiée sur Burkina 24 classés par date de parution"
search_omit: true
---

<ul class="post-list">
{% for post in site.categories.articles %}
  <li><article><a href="{{ site.url }}{{ post.url }}">{{ post.title }} <span class="entry-date"><time datetime="{{ post.date | date_to_xmlschema }}">{{ post.date | date: "%B %d, %Y" }}</time></span>{% if post.excerpt %} <span class="excerpt">{{ post.excerpt }}</span>{% endif %}</a></article></li>
{% endfor %}
</ul>
