---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---

This page is under construction.

# Publications
  * ``Does Immigration Boost Public Euroscepticism in European Union Member States?'' _European Union Politics_, forthcoming. DOI: 10.1177/14651165211030428.
      * **Abstract:** A number of studies have established a strong link between anti-immigration and Eurosceptic attitudes. But does this relationship necessarily imply that more immigration would increase public Euroscepticism in member states of the European Union? I evaluate this question by analyzing immigration data and Eurobarometer survey data over the period 2009–2017. The analysis shows no evidence that individual levels of Euroscepticism increase with actual levels of immigration. This result suggests that a strong link between anti-immigration and Eurosceptic attitudes does not necessarily translate into a strong link between immigration levels and public Euroscepticism. Public Euroscepticism can still be low even if immigration levels are high.

# Working Papers

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
