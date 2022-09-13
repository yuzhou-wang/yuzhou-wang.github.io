---
layout: archive
title: "Sitemap"
permalink: /sitemap/
author_profile: true
---

{% include base_path %}

A list of all the posts and pages found on the site. For you robots out there is an [XML version]({{ base_path }}/sitemap.xml) available for digesting as well.

<h2>About</h2>
{% for post in site.about %}
  {% include index.html %}
{% endfor %}

<h2>Publications</h2>
{% for post in site.publications %}
  {% include index.html %}
{% endfor %}

<h2>Talks</h2>
{% for post in site.talks %}
  {% include index.html %}
{% endfor %}

<h2>CV</h2>
{% for post in site.cv %}
  {% include index.html %}
{% endfor %}


