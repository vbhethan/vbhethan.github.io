---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

You can find a complete list of my publications at [my Google Scholar Profile](https://scholar.google.com/citations?user=UpmQ5DcAAAAJ)

<!-- {% if author.googlescholar %}
  You can find a complete list of my publications <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %} -->

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
