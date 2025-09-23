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

<span style='color:grey'>Clustering</span>
-------------------------------------------------------------------------

{% for post in site.publications reversed %}
  {% if post.topic contains 'clustering' %}
    {% include archive-single.html %}
  {% endif %}
{% endfor %}

<span style='color:grey'>Empirical Bayes</span>
-------------------------------------------------------------------------

{% for post in site.publications reversed %}
  {% if post.topic contains 'embayes' %}
    {% include archive-single.html %}
  {% endif %}
{% endfor %}

<span style='color:grey'>Other topics in statistics</span>
-------------------------------------------------------------------------
{% for post in site.publications reversed %}
  {% if post.topic contains 'others' %}
    {% include archive-single.html %}
  {% endif %}
{% endfor %}
