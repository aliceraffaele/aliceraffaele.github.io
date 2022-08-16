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
- Alice Raffaele and Matteo Zavatteri. *Reducing the Number of Disjuncts in DTPs*. August 2022.
- Matteo Zavatteri, Alice Raffaele, Dario Ostuni, and Romeo Rizzi. *An Interdisciplinary Experimental Evaluation on the Disjunctive Temporal Problem*. July 2022.
- Alice Raffaele and Romeo Rizzi. *A new decomposition for the Monotone Boolean Duality problem*. July 2021.
- Alice Raffaele, Romeo Rizzi, and Takeaki Uno. *Listing the bonds of a graph in Õ(n)-delay*. June 2021.
