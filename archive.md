---
layout: page
title: Archive
permalink: /archive/
---
{% assign posts_by_year = site.posts | group_by_exp:"post", "post.date | date: '%Y'" %}
{% for year in posts_by_year %}
  <h3>{{ year.name }}</h3>
  <ul>
    {% for post in year.items %}
      <li>
        <a href="{{ post.url | relative_url }}">{{ post.title }}</a>
        <span>{{ post.date | date: '%B %d' }}</span>
      </li>
    {% endfor %}
  </ul>
{% endfor %}
