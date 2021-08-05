---
title: Directory
permalink: /directory
---

All of the posts can be found below:

<ol>
  {% for post in site.posts reversed%}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ol>