---
title: "Publications"
permalink: /publications/
author_profile: true
---

{% include base_path %}

Below are selected publications and resources (links to PDFs / OpenReview / arXiv when available).

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
