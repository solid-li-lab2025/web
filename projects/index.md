---
title: Research
nav:
  order: 1
---

# {% include icon.html icon="fa-solid fa-university" %}Research Projects



## Featured

{% include list.html component="card" data="projects" filter="group == 'featured'" %}

{% include section.html %}

## Past

{% include list.html component="card" data="projects" filter="!group" style="small" %}


## Funding Agencies




{% capture content %}
  {% include figure.html imgage="/images/latech.png" %}
  {% include figure.html imgage="/images/photo.jpg" %}
  {% include figure.html imgage="images/latech.png" %}
  {% include figure.html imgage="images/latech.png" %}
  {% include figure.html imgage="images/latech.png" %}
{% endcapture %}

{%
  include grid.html
  content=content
%}
