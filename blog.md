---
layout: page
title: Blog
permalink: /blog/
description: Notes and writing by Riya Bisht.
---

<div class="blog-page">
  <p class="eyebrow">Notes and writing</p>
  <h1 class="blog-title">The blog<span class="accent-period">.</span></h1>

  <div class="blog-list">
    {% for post in site.posts %}
      <article class="blog-entry">
        <p class="blog-date">
          {% assign date_format = site.minima.date_format | default: "%b %-d, %Y" %}
          <time datetime="{{ post.date | date_to_xmlschema }}">{{ post.date | date: date_format }}</time>
        </p>
        <h2><a href="{{ post.url | relative_url }}">{{ post.title | escape }}</a></h2>
        {% if site.show_excerpts %}
          <p>{{ post.excerpt | strip_html | normalize_whitespace | truncate: 200 | escape }}</p>
        {% endif %}
        <a class="text-link" href="{{ post.url | relative_url }}">Read post <span aria-hidden="true">↗</span></a>
      </article>
    {% endfor %}
  </div>
</div>
