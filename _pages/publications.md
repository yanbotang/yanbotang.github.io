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

Works in Progress
======
* "Higher-Order Accurate Approximate Bayesian Inference using Adaptive Quadrature" with Blair Bilodeau and Alex Stringer
* "Higher-Order Approximations in High Dimensions" with Nancy Reid 
* "Asympotic Behaviour of the Modified Likelihood Root" with Nancy Reid
