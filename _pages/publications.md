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
- Antonino Andrea Carè, Alice Raffaele, Roberto Roberti, Sara Stoia, and Yanlu Zhao. *What If Robots Could Take the Metro? Potential Benefits in Integrating Public Transport with Last-mile Delivery*. March 2026 (submitted).
- Feilong Wang, Renata Mansini, Alice Raffaele, Filippo Ranza, and Roberto Roberti. *A DP-based Exact Method for the Submodular Knapsack Problem*. November 2025 (submitted).


&nbsp;
