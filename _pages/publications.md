---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

For the full publication list, see my [Google Scholar profile](https://scholar.google.com/citations?user=6cS9CVEAAAAJ&hl=en). Preprints are explicitly labelled below.

2026
-----

{% include recent-publications.html year=2026 %}

2025
-----

{% include recent-publications.html year=2025 %}

2024
-----

{% include recent-publications.html year=2024 %}

Earlier Selected Publications
-----

See the [homepage](/#selected-publications) for additional selected publications, including work published before 2024.

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
