---
layout: default
title: Kim Hokkanen
name: Kim Hokkanen
---

# Index

Uuga booga buggy boo!

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>
