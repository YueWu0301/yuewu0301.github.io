---
layout: archive
title: "Intern"
permalink: /intern/
author_profile: true
---

Here are several intern experiences and what I do during these periods ~







{% if site.author.googlescholar %}
  <div class="wordwrap">You can also find my articles on <a href="{{site.author.googlescholar}}">my Google Scholar profile</a>.</div>
{% endif %}

{% include base_path %}

{% for post in site.intern reversed %}
  {% include archive-single.html %}
{% endfor %}
