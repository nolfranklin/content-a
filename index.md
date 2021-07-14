---
title: Homepage A
tags:
  - one
  - two
---
# Hello world v.4

This is a paragraph.

This is a content repo for A and demonstraights tags.

{%- for post in collections.all -%}
  <li><a href="{{ post.url }}">{{ post.url }}</a></li>
{%- endfor -%}

<hr />

## Collections "One"

{%- for post in collections.one -%}
  <li><a href="{{ post.url }}">{{ post.url }}</a></li>
{%- endfor -%}

<hr />

## Collections "Two"

{%- for post in collections.two -%}
  <li><a href="{{ post.url }}">{{ post.url }}</a></li>
{%- endfor -%}
