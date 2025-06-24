---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

Here are some selected publications.  {% if site.author.googlescholar %} You can
find a fuller list on [my Google Scholar profile page]({{
site.author.googlescholar }}). {% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
