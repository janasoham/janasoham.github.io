---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---
(Authors lists usually in alphabetical order of surnames. Exceptions denoted with "*".)

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% if post.topic contains 'mixture_modeling' %}
    {% include archive-single.html %}
  {% endif %}
{% endfor %}
