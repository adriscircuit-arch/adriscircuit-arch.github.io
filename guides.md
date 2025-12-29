---
layout: page
title: Guides ⚙️ 
permalink: /guides/
---


Selected templates and concise guides for multidisciplinary work.

{% if site.posts.size > 0 %}
  {% for post in site.posts %}
  <article class="guide">
    <h3><a href="{{ post.url }}">{{ post.title }}</a></h3>
    <div class="meta">
      <time>{{ post.date | date: "%B %Y" }}</time>
      {% if post.tags %}
        <span class="tags">
          {% for tag in post.tags %}
            <span class="tag">{{ tag }}</span>
          {% endfor %}
        </span>
      {% endif %}
    </div>
    <p>{{ post.excerpt | strip_html | truncate: 140 }}</p>
  </article>
  {% endfor %}
{% else %}
  <div class="empty">
    <p>Guides are added occasionally as useful patterns emerge.</p>
    <p><a href="/updates">Get notified</a> when new guides are published.</p>
  </div>
{% endif %}

<style>
.guide { margin-bottom: 2.5rem; padding-bottom: 2rem; border-bottom: 1px solid #f0f0f0; }
.guide h3 { margin-bottom: 0.4rem; }
.guide h3 a { text-decoration: none; }
.meta { display: flex; align-items: center; gap: 1rem; margin-bottom: 0.8rem; font-size: 0.85rem; color: #777; }
.tags { display: flex; gap: 0.3rem; }
.tag { background: #f5f5f5; padding: 0.2rem 0.6rem; border-radius: 2px; }
.empty { text-align: center; padding: 3rem; color: #777; line-height: 1.6; }
</style>
