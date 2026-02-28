---
layout: default
title: Publications
permalink: /publications/
description: "Publications by Spyridon Giagtzoglou on Generative AI, optimization, and evaluation."
---

<div class="section-header">
  <h1>Publications</h1>
</div>

{% assign pubs = site.data.publications %}
{% if pubs and pubs.size > 0 %}

  <ul class="publication-list">
    {% for pub in pubs %}
    <li class="publication-item">
      <div class="pub-title">{{ pub.title }}</div>
      <div class="pub-authors">{{ pub.authors }}</div>
      <div class="pub-venue"><em>{{ pub.venue }}</em>, {{ pub.year }}</div>
      {% if pub.links %}
      <div class="pub-links">
        {% for link in pub.links %}
        <a href="{{ link.url }}" target="_blank" rel="noopener noreferrer" class="badge">{{ link.label }}</a>
        {% endfor %}
      </div>
      {% endif %}
    </li>
    {% endfor %}
  </ul>

{% else %}

  <div class="pubs-empty">
    <div class="empty-icon">
      <i class="fas fa-flask" aria-hidden="true"></i>
    </div>
    <p><strong>Publications coming soon.</strong></p>
    <p class="empty-sub">Research is currently in progress — please check back for updates.</p>
  </div>

{% endif %}
