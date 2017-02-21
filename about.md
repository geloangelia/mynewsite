---
layout: page
title: About
permalink: /profile
---

<h1>VC LIST!!</h1>

<ul>
{% for list in site.data.vclist %}
  <li><a href="{{ list.Name }}">{{list.Name}}</a></li>
{% endfor %}
</ul>
