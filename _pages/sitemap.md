---
layout: archive
title: "Sitemap"
permalink: /sitemap/
author_profile: true
---

{% include base_path %}

A list of the main links found on the site. 

{% for post in site.pages %}
  {% include archive-single.html %}
{% endfor %}

{% for collection in site.collections %}
  {% unless collection == "workingpapers" %}
  {% for post in collection.docs %}
    {% unless collection.output == false or collection.label == "posts" %}
    {% include archive-single.html %}
    {% endunless %}
  {% endfor %}
  {% endunless %}
{% endfor %}

