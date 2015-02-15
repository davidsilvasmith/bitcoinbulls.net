---
title: Bitcoin Bull Authors
layout: sidebar-container
includeJoin: 1
permalink: /blog/authors/
---
{% assign delimiter = "," %}
{% assign names_str = "" %}

  {% for post in site.posts %}
    {% assign names_arr = names_str | split: delimiter %}
    {% unless names_arr contains post.author %}
        {% assign names_str = names_str | append: delimiter | append: post.author %}
    {% endunless %}
  {% endfor %}
{% assign names_str = names_str | remove_first: delimiter %}

# Bitcoin Bull Authors

{% assign names_arr = names_str | split: delimiter %}
{% for name in names_arr %}
{% assign author = site.data.people.[name] %}
  <ul>
  	<div itemscope itemtype="http://schema.org/Person">
      {% if author.image and author.name %} <div itemprop="photo"><img src="{{author.image}}" alt="{{author.name}}" title="{{author.name}}"/> {% endif %}
      {% if author.name %} <div itemprop="name"><strong>{{author.name}}</strong></div> {% endif %}
      {% if author.description %}<div itemprop="description">{{author.description}}</div> {%endif %}
      {% if author.email %}<a href="mailto:{{author.email}}"><div itemprop="email">dave@bitcoinbulls.net</div></a>{% endif %}
    </div>
  </ul>
{% endfor %}