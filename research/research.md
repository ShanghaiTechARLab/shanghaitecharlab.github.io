---
layout: page
title: Research
permalink: /research/
subtitle: 
---

<h2>{{ page.title }}</h2>
<p>Latest Articles</p>
<ul>
　　{% for post in site.posts %}
　　　　<li>{{ post.date | date_to_string }} <a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a></li>
　　{% endfor %}
</ul>









