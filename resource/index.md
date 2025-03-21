---
title: Tools
nav:
  order: 5
  tooltip: Important resources for research
---

# {% include icon.html icon="fa-solid fa-wrench" %} Important tools and links

Tools, websites, programs, and tutorials that are used in our lab.


{% include search-box.html %}
{% include search-info.html %}



{% include section.html %}

{% capture content %}
  
  {% include list.html
  data="resources"
  component="resource-excerpt" %}


{% endcapture %}

{%
  include grid.html
  content=content
%}

