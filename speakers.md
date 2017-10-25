---
title: Speakers
layout: default
permalink: "/speakers"
---

<ul class="speakers-grid">
{% for speaker in site.speakers %}
  <li class="speaker">
    <h1 class="speaker-name">{{ speaker.title }}</h1>
    <h2 class="speaker-title">{{ speaker['title and organization'] }}</h2>
    <img src="{{ speaker.photo }}" class="speaker-photo">
  </li>
{% endfor %}
</ul>
