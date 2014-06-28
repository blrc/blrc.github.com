---
layout: page
title: Bangalore
tagline: coolest city ever!
---
{% include JB/setup %}

<ul>
  {% for post in site.posts %}
    <h2><a href="{{ post.url }}">{{ post.title }}</a></h2>
	<br/>
	<p>{{post.content}}</p>
  {% endfor %}
</ul>


