---
title: Contact
nav:
  order: 6
  tooltip: Email, address, and location
---

# {% include icon.html icon="fa-regular fa-envelope" %}Contact

We always welcome motivated high school, undergraduate, and graduate students with different backgrounds to join our team. Feel free to shoot Dr. Li an email if you want to work with us :)

Currently, we don't have postdoc openings. 

{%
  include button.html
  type="email"
  text="tianyuli@ucsb.edu"
  link="tianyuli@ucsb.edu"
%}
{%
  include button.html
  type="phone"
  text="(xxx) xxx-xxxx"
  link="+x-xxx-xxx-xxxx"
%}
{%
  include button.html
  type="address"
  tooltip="Our location on Google Maps for easy navigation"
  link="https://www.google.com/maps"
%}

{% include section.html %}

{% capture col1 %}

{%
  include figure.html
  image="images/cubic_packing.png"
  caption="cubic lattice"
%}

{% endcapture %}

{% capture col2 %}

{%
  include figure.html
  image="images/graphene.jpg"
  caption="hexagonal lattice"
%}

{% endcapture %}

{% include cols.html col1=col1 col2=col2 %}

{% include section.html dark=true %}

{% capture col1 %}
We apply chemical intuition.
{% endcapture %}

{% capture col2 %}
Physics enables the fundamental understanding.
{% endcapture %}

{% capture col3 %}
We perform interdisciplinary materials research.
{% endcapture %}

{% include cols.html col1=col1 col2=col2 col3=col3 %}
