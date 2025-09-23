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

<h2 style="border-bottom: 2px solid #ccc; color: grey;">Computational imaging</h2>
{% for post in site.publications reversed %}
  {% if post.topic contains 'computational_imaging' %}
    {% include archive-single.html %}
  {% endif %}
{% endfor %}

<h2 style="border-bottom: 2px solid #ccc; color: grey;">Deep learning</h2>
{% for post in site.publications reversed %}
  {% if post.topic contains 'deep_learning' %}
    {% include archive-single.html %}
  {% endif %}
{% endfor %}

<h2 style="border-bottom: 2px solid #ccc; color: grey;">Clustering</h2>
{% for post in site.publications reversed %}
  {% if post.topic contains 'clustering' %}
    {% include archive-single.html %}
  {% endif %}
{% endfor %}

<h2 style="border-bottom: 2px solid #ccc; color: grey;">Empirical Bayes</h2>
{% for post in site.publications reversed %}
  {% if post.topic contains 'embayes' %}
    {% include archive-single.html %}
  {% endif %}
{% endfor %}

<h2 style="border-bottom: 2px solid #ccc; color: grey;">Other topics in statistics</h2>
{% for post in site.publications reversed %}
  {% if post.topic contains 'others' %}
    {% include archive-single.html %}
  {% endif %}
{% endfor %}

