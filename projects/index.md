---
title: Research
nav:
  order: 1
---

# {% include icon.html icon="fa-solid fa-university" %}Research Projects



## Featured

{% include list.html component="card" data="projects" filter="group == 'featured'" %}

{% include section.html %}


## Techniques

{% include list.html component="card" data="projects" filter="group == 'technique'" %}

## Past

{% include list.html component="card" data="projects" filter="!group" style="small" %}


## Funding Agencies
{% capture content %}
  {% include figure.html 
  image="images/LouisianaTechSeal.png" 
  caption="LA Tech"
  link="https://www.latech.edu/" %}

  {% include figure.html image="images/photo.jpg" %}

  {% include figure.html image="images/photo.jpg" %}

  {% include figure.html image="images/photo.jpg" %}

  {% include figure.html image="images/photo.jpg" %}

{% endcapture %}

{%
  include grid.html
  content=content
  style="square"
%}



