---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

Visit my [Google scholar page](https://scholar.google.com/citations?user=zfW6nsMAAAAJ&hl=en) for the most up-to-date publication list. 

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
