---
title: Pokemons list
tags: primary
layout: base
---
<ul>
 {%- for species in pokemon %}
 <li><a href="{{ species.name | slugify }}">{{ species.name }}</a></li>
 {% endfor -%}
</ul>