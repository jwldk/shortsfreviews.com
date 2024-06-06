---
layout: page
title: Review index
permalink: /review-index/
---
<p><a href="#rating">Rating</a> | <a href="#decade">Decades</a> | <a href="#magazines">Magazines</a> | <a href="#anthologies">Anthologies</a></p>
<h2 id="rating">Stories by rating</h2>
  <h3>5&#11089;</h3>
  <p>Amazing. Award worthy</p>
  <ul>
    {% assign sorted_posts = site.tags.5 | sort: 'title' %}
    {% for post in sorted_posts %}
      <li><a href="{{ post.url }}">{{ post.title }}</a></li>
    {% endfor %}
  </ul>
  <h3>4&#11089;</h3>
  <p>Very good. Best of the year material</p>
  <ul>
    {% assign sorted_posts = site.tags.4 | sort: 'title' %}
    {% for post in sorted_posts %}
      <li><a href="{{ post.url }}">{{ post.title }}</a></li>
    {% endfor %}
  </ul>
  <h3>3&#11089;</h3>
  <p>Good story. Worth reading</p>
  <ul>
    {% assign sorted_posts = site.tags.3 | sort: 'title' %}
    {% for post in sorted_posts %}
      <li><a href="{{ post.url }}">{{ post.title }}</a></li>
    {% endfor %}
  </ul>
  <h3>2&#11089;</h3>
  <p>Just okay</p>
  <ul>
    {% assign sorted_posts = site.tags.2 | sort: 'title' %}
    {% for post in sorted_posts %}
      <li><a href="{{ post.url }}">{{ post.title }}</a></li>
    {% endfor %}
  </ul>
  <h3>1&#11089;</h3>
  <p>Not recommended</p>
  <ul>
    {% assign sorted_posts = site.tags.1 | sort: 'title' %}
    {% for post in sorted_posts %}
      <li><a href="{{ post.url }}">{{ post.title }}</a></li>
    {% endfor %}
  </ul>
<h2 id="decade">Stories by decade</h2>
  <h3>1940s</h3>
  <ul>
    {% assign sorted_posts = site.tags.1940s | sort: 'title' %}
    {% for post in sorted_posts %}
      <li><a href="{{ post.url }}">{{ post.title }}</a></li>
    {% endfor %}
  </ul>
  <h3>1950s</h3>
  <ul>
    {% assign sorted_posts = site.tags.1950s | sort: 'title' %}
    {% for post in sorted_posts %}
      <li><a href="{{ post.url }}">{{ post.title }}</a></li>
    {% endfor %}
  </ul>
  <h3>1960s</h3>
  <ul>
    {% assign sorted_posts = site.tags.1960s | sort: 'title' %}
    {% for post in sorted_posts %}
      <li><a href="{{ post.url }}">{{ post.title }}</a></li>
    {% endfor %}
  </ul>
  <h3>1970s</h3>
  <ul>
    {% assign sorted_posts = site.tags.1970s | sort: 'title' %}
    {% for post in sorted_posts %}
      <li><a href="{{ post.url }}">{{ post.title }}</a></li>
    {% endfor %}
  </ul>
  <h3>1980s</h3>
  <ul>
    {% assign sorted_posts = site.tags.1980s | sort: 'title' %}
    {% for post in sorted_posts %}
      <li><a href="{{ post.url }}">{{ post.title }}</a></li>
    {% endfor %}
  </ul>
  <h3>1990s</h3>
  <ul>
    {% assign sorted_posts = site.tags.1990s | sort: 'title' %}
    {% for post in sorted_posts %}
      <li><a href="{{ post.url }}">{{ post.title }}</a></li>
    {% endfor %}
  </ul>
  <h3>2000s</h3>
  <ul>
    {% assign sorted_posts = site.tags.2000s | sort: 'title' %}
    {% for post in sorted_posts %}
      <li><a href="{{ post.url }}">{{ post.title }}</a></li>
    {% endfor %}
  </ul>
  <h3>2010s</h3>
  <ul>
    {% assign sorted_posts = site.tags.2010s | sort: 'title' %}
    {% for post in sorted_posts %}
      <li><a href="{{ post.url }}">{{ post.title }}</a></li>
    {% endfor %}
  </ul>
  <h3>2020s</h3>
  <ul>
    {% assign sorted_posts = site.tags.2020s | sort: 'title' %}
    {% for post in sorted_posts %}
      <li><a href="{{ post.url }}">{{ post.title }}</a></li>
    {% endfor %}
  </ul>
<h2 id="magazines">Magazines</h2>
  <h3>Asimov's Science Fiction</h3>
  <ul>
    {% assign sorted_posts = site.tags.asimovs | sort: 'title' %}
    {% for post in sorted_posts %}
      <li><a href="{{ post.url }}">{{ post.title }}</a></li>
    {% endfor %}
  </ul>
  <h3>Analog Science Fiction & Fact</h3>
  <ul>
    {% assign sorted_posts = site.tags.analog | sort: 'title' %}
    {% for post in sorted_posts %}
      <li><a href="{{ post.url }}">{{ post.title }}</a></li>
    {% endfor %}
  </ul>
  <h3>Clarkesworld</h3>
  <ul>
    {% assign sorted_posts = site.tags.clarkesworld | sort: 'title' %}
    {% for post in sorted_posts %}
      <li><a href="{{ post.url }}">{{ post.title }}</a></li>
    {% endfor %}
  </ul>
  <h3>Fantasy & Science Fiction</h3>
  <ul>
    {% assign sorted_posts = site.tags.fsf | sort: 'title' %}
    {% for post in sorted_posts %}
      <li><a href="{{ post.url }}">{{ post.title }}</a></li>
    {% endfor %}
  </ul>
<h2 id="anthologies">Anthologies</h2>
  <ul>
    {% assign sorted_posts = site.categories.anthologies | sort: 'title' %}
    {% for post in sorted_posts %}
      <li><a href="{{ post.url }}">{{ post.title }}</a></li>
    {% endfor %}
  </ul>
