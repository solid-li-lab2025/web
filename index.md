---
---

# Welcome!

Our Lab performs interdisciplinary research to synthesize and understand the  structure dynamics of novel solid state materials. Currently we are interested in energy storage materials, quantum materials, and heterocatalysts. We welcome students with backgrounds in chemistry, physics, and (chemical, materials, mechanical) engineering to join us :)

{% include section.html %}

## Highlights

{% capture text %}

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.

{%
  include button.html
  link="research"
  text="Learn more about our research"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}

{% endcapture %}

{%
  include feature.html
  image="images/photo.jpg"
  link="research"
  title="Our Research"
  text=text
%}

{% capture text %}

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.

{%
  include button.html
  link="projects"
  text="Browse our publication"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}

{% endcapture %}

{%
  include feature.html
  image="images/photo.jpg"
  link="projects"
  title="Most recent publication"
  flip=true
  style="bare"
  text=text
%}

{% capture text %}

Tianyu finished his postdoc fellowship at UCSB. I will miss the life in Santa Barbara and mentorship from both Raphaele and Ram.

{%
  include button.html
  link="team"
  text="learn about past events"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}

{% endcapture %}

{%
  include feature.html
  image="images/photo.jpg"
  link="blog"
  title="Recent events"
  text=text
%}
