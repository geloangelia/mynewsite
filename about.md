---
layout: page
title: About
permalink: /profile
---

<h1>VC LIST!!!</h1>

<ul>
{% for person in site.data.member %}
  <li><a href="{{ person.full_name | datapage_url: 'people' }}">{{person.full_name}}</a></li>
{% endfor %}
</ul>