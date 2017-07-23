---
layout: default
title: Blog
permalink: /blog/
meta: Welcome to this wonderful blog
---

<ul>
  {% for blogs in site.posts%}
  <li>
  <a href="{{site.baseurl}}/{{blogs.permalink}}">{{blogs.title}}</a>
  <p>{{blogs.meta}}</p>
</li>
{% endfor %}
</ul>
