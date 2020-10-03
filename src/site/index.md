---
title: JuniorDev
subtitle: A friendly place for developers to level up their skills<br /> Made by <a href="https://twitter.com/jessicaewest">Jess</a> and <a href="https://twitter.com/stevekinney">Steve</a>.
layout: layouts/base.njk
---


## About blurb

## Workshops

- AWS Solution Certification
- Building your brand as a software engineer
- Choosing your JAMStack solution
- Front end architecture 

## Recent Posts

<ul class="listing">
{%- for page in collections.post -%}
  <li>
    <a href="{{ page.url }}">{{ page.data.title }}</a> -
    <time datetime="{{ page.date }}">{{ page.date | dateDisplay("LLLL d, y") }}</time>
  </li>
{%- endfor -%}
</ul>






