---
layout: archive
title: "Press articles"
permalink: /press/
author_profile: true
---

{% if site.author.googlescholar %}
  <div class="wordwrap">A list of press articles on my research<
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
