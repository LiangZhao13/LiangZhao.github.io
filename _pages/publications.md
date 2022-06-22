---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---
*: Corresponding author; #: Contributed equally

Journal Articles
===
* Zhao, L., Wang, F., Bai, Y., 2022. Route planning for autonomous vessels based on improved artificial fish swarm algorithm. Ships and Offshore Structures 1–10. https://doi.org/10.1080/17445302.2022.2081423








{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
