---
layout: page
title: About
permalink: /about/
---

<h1>People!! (generated from YAML)</h1>

<ul>
{% for person in site.data.member %}
  <li><a href="{{ person.full_name | datapage_url: '/people' }}">{{person.full_name}}</a></li>
{% endfor %}
</ul>
