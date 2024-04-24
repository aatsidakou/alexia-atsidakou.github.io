---
layout: archive
title: "Publication List"
permalink: /publications/
author_profile: true
---

Bayesian Fixed-Budget Best-Arm Identification

{% if site.author.googlescholar %}
  <div class="wordwrap">You can also find my publications on my Google Scholar <a href="{{site.author.googlescholar}}">profile</a>.</div>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
