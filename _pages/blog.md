---
layout: archive
title: "Blog"
permalink: /blog/
author_profile: true
---

Here are several Blogs!







{% if site.author.googlescholar %}
  <div class="wordwrap">You can also find my articles on <a href="{{site.author.googlescholar}}">my Google Scholar profile</a>.</div>
{% endif %}

{% include base_path %}

{% for post in site.blog reversed %}
  {% include archive-single.html %}
{% endfor %}
