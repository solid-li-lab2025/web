---
title: Research
nav:
  order: 1
---

# {% include icon.html icon="fa-solid fa-wrench" %}Projects



## Featured

{% include list.html component="card" data="projects" filter="group == 'featured'" %}

{% include section.html %}

## Past

{% include list.html component="card" data="projects" filter="!group" style="small" %}


## Funding Agencies

{% capture content %}
  ![](/images/photo.png)

  ![](/images/photo.png)

  ![](/images/photo.png)
{% endcapture %}

{%
  include grid.html
  content=content
  style="square"
%}
