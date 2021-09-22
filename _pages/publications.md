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
* "Variability of Astrophysical Jets" with Eileen Meyer, Aamil Shaik and  Nancy Reid 
* "Asympotic Behaviour of the Modified Likelihood Root" with Nancy Reid
