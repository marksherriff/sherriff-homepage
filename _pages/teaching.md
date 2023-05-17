---
layout: archive
title: "Teaching"
permalink: /teaching/
author_profile: true
---

_Courses ordered by most recently taught._

{% include base_path %}

{% for post in site.teaching reversed %}
  {% include archive-single.html %}
{% endfor %}
