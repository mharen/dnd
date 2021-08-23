---
title: Dungeons and Dragons sessions
---

# {{ page.title }}

<ul>
  {% for post in site.posts %}
    <li>
        {{ post.date | date: "%Y-%m-%d" }} <a href="{{ post.url | prepend: site.baseurl }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>