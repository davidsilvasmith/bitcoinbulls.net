---
title: Bitcoin Bulls Blog for Bitcoin believers.
permalink: /blog/
---

<ul>
  {% for post in site.posts %}
    <li>

      {% assign foundImage = 0 %}
      {% assign images = post.content | split:"<img " %}
      {% for image in images %}
      	{% if image contains 'src' %}
      		
      		{% if foundImage == 0 %}
      			{% assign html = image | split:"/>" | first %}
      			<img {{ html }} />
      			{% assign foundImage = 1 %}
      		{% endif %}
      	{% endif %}
      {% endfor %}

      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>