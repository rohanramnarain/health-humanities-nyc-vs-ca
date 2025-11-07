---
layout: home
title: "NYC vs California — Health & Humanities"
---

Welcome! This project compares **New York City** and **California** through a **health & humanities** lens, using a minimalist static site (Jekyll + GitHub Pages).

Below is a quick, human-readable comparison that’s generated from a small dataset in `_data/compare.yml`.

{% for t in site.data.compare.topics %}
  {% include card.html title=t.label nyc=t.nyc ca=t.ca note=t.note %}
{% endfor %}

> 
