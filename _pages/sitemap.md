---
layout: archive
title: "Sitemap"
permalink: /sitemap/
author_profile: true
---

{% include base_path %}

A list of all the pages and publications found on the site. There is also an [XML version]({{ base_path }}/sitemap.xml) available.

<h2>Pages</h2>
{% include archive-pages.html %}

<h2>Publications</h2>
{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
