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

<span style='color:grey'>Computational imaging</span>
-------------------------------------------------------------------------

{% for post in site.publications reversed %}
  {% if post.topic contains 'computational_imaging' %}
    {% include archive-single.html %}
  {% endif %}
{% endfor %}

<span style='color:grey'>Deep learning</span>
-------------------------------------------------------------------------

{% for post in site.publications reversed %}
  {% if post.topic contains 'deep_learning' %}
    {% include archive-single.html %}
  {% endif %}
{% endfor %}

<span style='color:grey'>Mixture modeling</span>
-------------------------------------------------------------------------

{% for post in site.publications reversed %}
  {% if post.topic contains 'mixture_modeling' %}
    {% include archive-single.html %}
  {% endif %}
{% endfor %}
