---
layout: page
title: About
permalink: /profile
---

<h1>VC LIST!!</h1>

<ul>
{% for list in site.data.vclist %}
  <li><a href="{{ page_Name | datapage_url: dir }}">{{list.Name}}</a></li>
{% endfor %}
</ul>
