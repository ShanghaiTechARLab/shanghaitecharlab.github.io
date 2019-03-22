---
layout: page
title: Research
permalink: /research/
subtitle: 
---

<h2>{Latest Articles}</h2>
<ul>
　　{% for post in site.posts %}
       <li> <a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a></li>
　　　　<li>{{ post.date | date_to_string }}</li>
　　{% endfor %}
</ul>








