---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

<b>Selected Publications</b> (For a complete list of my articles, please refer to [my Google Scholar profile](https://scholar.google.com/citations?user=EfzlIqkAAAAJ&hl=en&oi=ao){:target="\_blank"})

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
