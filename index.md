---
---

## Research Interest

P4MARS is an interdisciplinary research group focused on Perception and AI for Manufacturing, Robotics, and Space. Our research interests include geometric and semantic scene understanding, active perception, and distributed perception, with the application to robotics in manufacturing and space domains.

{% include section.html %}

## News
{%
  include button.html
  link="posts"
  text="See all events"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}


## Highlights

{% capture text %}

<!-- Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. -->

{%
  include button.html
  link="research"
  text="See our publications"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}

{% endcapture %}

{%
  include feature.html
  image="images/research/T-FunS3D_teaser.png"
  fit="contain"
  link="research"
  title="Our Research"
  text=text
%}

{% capture text %}

{%
  include button.html
  link="projects"
  text="Browse our projects"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}

{% endcapture %}

{%
  include feature.html
  image="images/photo.jpg"
  link="projects"
  title="Our Projects"
  flip=true
  style="bare"
  text=text
%}

{% capture text %}

{%
  include button.html
  link="team"
  text="Meet our team"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}

{% endcapture %}

<!-- ToDo: Add group picture -->
{%
  include feature.html
  image="images/photo.jpg"
  link="team"
  title="Our Team"
  text=text
%}
