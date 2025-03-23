---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---
{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

&nbsp;

# Submitted:
- Alice Raffaele, Demetrio Salvatore Laganà, and Roberto Roberti. *Robust Policies for a Multi-Period Fleet Sizing Problem with Demand Uncertainty*. August 2024 (submitted), December 2024 (invited revision).

&nbsp;
