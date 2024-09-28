---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---


<!-- (*Note: In publications marked with **, all authors are sorted by alphabetic order.*) -->
You can also find my articles on <u><a href="https://scholar.google.com/citations?user=QhrqlcwAAAAJ&hl=en">my Google Scholar profile</a>.</u>

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
