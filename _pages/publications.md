---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---
(Author list in alphabetical order of surnames, unless mentioned)

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
