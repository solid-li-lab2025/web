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

{% capture col1 %}
{% include figure.html 
  image="images/LouisianaTechSeal.png" 
  caption="LA Tech"
  link="https://www.latech.edu/" %}
{% endcapture %}

{% capture col2 %}
{% include figure.html image="images/photo.jpg" %}
{% endcapture %}

{% capture col3 %}
{% include figure.html image="images/photo.jpg" %}
{% endcapture %}

{% capture col4 %}
{% include figure.html image="images/photo.jpg" %}
{% endcapture %}

{% capture col5 %}
{% include figure.html image="images/photo.jpg" %}
{% endcapture %}

{% capture col6 %}
{% include figure.html image="images/photo.jpg" %}
{% endcapture %}

{% include cols.html col1=col1 col2=col2 col3=col3 col4=col4 col5=col5 col6=col6 %}







