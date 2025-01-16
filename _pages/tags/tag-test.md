---
title: "test"
layout: archive
permalink: /tags/test/
---

{% assign posts = site.tags.test %}
{% if posts %}
  {% for post in posts %}
    {% include archive-single.html type=page.entries_layout %}
  {% endfor %}
{% else %}
  <p>해당 태그에 대한 포스트가 없습니다.</p>
{% endif %}
