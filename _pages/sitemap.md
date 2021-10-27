---
layout: archive
title: "Sitemap"
permalink: /sitemap/
author_profile: true
---

{% include base_path %}

A list of all the posts and pages found on the site. For you robots out there is an [XML version]({{ base_path }}/sitemap.xml) available for digesting as well.

{% for post in site.pages %}
  {% include archive-single.html %}
{% endfor %}

{% for collection in site.collections %}
  {% for post in collection.docs %}
    {% unless collection.output == false or collection.label == "posts" %}
    {% include archive-single.html %}
    {% endunless %}
  {% endfor %}
{% endfor %}





