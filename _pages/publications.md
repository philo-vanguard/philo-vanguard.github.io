---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

In publications marked with **, authors are ordered alphabetically. In the other publications, authors are ordered by contribution.
You can also find my articles on <u><a href="https://scholar.google.com/citations?user=Zu3XLB8AAAAJ&hl=en">my Google Scholar profile</a>.</u>

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
