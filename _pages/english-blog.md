---
layout: archive
title: "English Blog"
permalink: /english-blog/
author_profile: true
---

{% include base_path %}

{% assign posts = site.posts | where: "lang", "en" %}

{% for post in posts %}
  {% include archive-single.html %}
{% endfor %}

{% if posts.size == 0 %}
  <p>No English blog posts yet. Stay tuned!</p>
{% endif %}
