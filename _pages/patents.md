---
layout: archive
title: "patents"
permalink: /patents/
author_profile: true
---

{% include base_path %}

{% for post in site.patents reversed %}
  {% include archive-single.html %}
{% endfor %}

{% if site.author.googlescholar %}
  <div class="wordwrap">You can also find my patents on <a href="{{site.author.googlescholar}}">my Google Scholar profile</a>.</div>
{% endif %}
