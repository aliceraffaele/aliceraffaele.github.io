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
- Feilong Wang, Renata Mansini, Alice Raffaele, Filippo Ranza, and Roberto Roberti. *A DP-based Exact Method for the Submodular Knapsack Problem*. November 2025 (submitted).


&nbsp;
