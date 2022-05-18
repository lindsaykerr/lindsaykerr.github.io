---
title: Here be a blog
layout: posts
description: "Blog containing rantings, ramblings and ponderings on software development and technology"
keywords: ["blog", "posts", "information", "software", "programming"]
permalink: /blog/
---

{% for post in site.posts %}
  <article class="list-item">
    <header>
      <h3 class="title link"><a href="{{ post.url }}">{{ post.title }}</a></h3>
      <span class="date"><time datetime="{{post.date}}">{{post.date | date: "%-d %b %Y"}}</time></span>
    </header>
    <div class="excerpt">
      {{ post.excerpt}}
    </div>
  </article>
{% endfor %}

