---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

## Working Papers
* Product Bundling, Joint Markups and Trade liberalization (*Job Market Paper*)

{% include base_path %}

{% for post in site.research reversed %}
  {% include archive-single.html %}
{% endfor %}

## Work in Progress
* Product Bundling in International Markets with [Ebehi Iyoha](https://ebehii.github.io) and [Joel Rodrigue](https://joelrodrigue.com)
* Robust Inference in Differentiated Products Demand Analysis with Trimmed Infinitesimal Shares with [Yuya Sasaki](https://sites.google.com/site/yuyasasaki/)
