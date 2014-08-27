---
title: Bitcoin Bulls Blog for Bitcoin believers.
permalink: /blog/
---

<ul>
  {% for post in site.posts %}
    <li>    	
<a href="{{ post.url }}">
	<p>{{post.date | date: "%B %d, %Y" }}</p>
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
      <p>
      {{ post.excerpt }}
      </p>
      <p class="btn btn-md btn-success" role="button">READ POST
      </p>
      <br />
      <br />

  </a>
    </li>
  {% endfor %}
</ul>