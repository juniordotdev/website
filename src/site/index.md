---
title: Junior.dev
subtitle: A friendly place for developers to level up their skills<br /> Made by <a href="https://twitter.com/jessicaewest">Jess</a> and <a href="https://twitter.com/stevekinney">Steve</a>.
layout: layouts/base.njk
---

## What is this?

Are you just getting started in your career as a software engineer? Are you looking for a community?

Junior.dev offers intensive, four-to-six week workshops for learning new skills—both technical as well as career oriented. With our workshops, you'll have dedicated mentorship and a community of peers to learn and grow with.

## Workshops

We're in the process of putting together the curriculum for our first series of workshops. Here are some of the topics we're kicking around:

- Architecting for the cloud with Amazon Web Services
- Building your brand as a software engineer
- Choosing your JAMStack solution
- Front-end architecture

## Recent Posts

<ul class="listing">
{%- for page in collections.post -%}
  <li>
    <a href="{{ page.url }}">{{ page.data.title }}</a> -
    <time datetime="{{ page.date }}">{{ page.date | dateDisplay("LLLL d, y") }}</time>
  </li>
{%- endfor -%}
</ul>
