---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

My research interest spans the field of probabilistic machine learning, and are motivated by the need for the effective and efficient deployment of probabilistic machine learning techniques to improve decision making and prediction in the presence of uncertainty.

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
