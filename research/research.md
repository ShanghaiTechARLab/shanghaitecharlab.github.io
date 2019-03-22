---
layout: page
title: Research
permalink: /research/
subtitle: 研究内容
---

<h2>Latest Articles</h2>
<ul>
　　{% for post in site.posts %}
       <li><a href="{{ site.baseurl }}{{ post.url }}"></a></li>
　　{% endfor %}
</ul>

<!--        <li>{{ post.date | date_to_string }} <a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a></li> -->








