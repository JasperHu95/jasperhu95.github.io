---
layout: archive
title: "Chinese Blog"
permalink: /chinese-blog/
author_profile: true
---

{% include base_path %}

{% assign posts = site.posts | where: "lang", "zh" %}

{% for post in posts %}
  {% include archive-single.html %}
{% endfor %}

{% if posts.size == 0 %}
  <p>No Chinese blog posts yet. Stay tuned!</p>
{% endif %}
