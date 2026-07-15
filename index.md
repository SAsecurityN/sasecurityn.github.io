---
layout: default
---

I'm **Said-Abbosxon Nabijonov** — Professional Penetration Tester, who has started his journey in cyber back in May 2024.

## log

<ul class="post-list">
{% for post in site.posts %}
  <li>
    <time datetime="{{ post.date | date_to_xmlschema }}">{{ post.date | date: "%Y-%m-%d" }}</time>
    <a href="{{ post.url | relative_url }}">{{ post.title }}</a>
  </li>
{% endfor %}
</ul>
