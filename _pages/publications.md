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


2023
===

[TIP2022](https://ieeexplore.ieee.org/abstract/document/9725265) Structure-aware positional transformer for visible-infrared person re-identification. Cuiqun Chen, Mang Ye, Meibin Qi, Jingjing Wu, Jianguo Jiang, Chia-Wen Lin.

![](images/tip2022.png#pic_left=200x300)
