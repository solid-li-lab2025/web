---
title: Tools
nav:
  order: 5
  tooltip: Important resources for research
---

# {% include icon.html icon="fa-solid fa-wrench" %} Important tools and links

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.
Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.


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

