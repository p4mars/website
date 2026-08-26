---
---
## Research Interest

p4MARS (Perception for Manufacturing, Automation, Robotics and Space) is an interdisciplinary research group at the intersection of robotics, agentic AI, and cognitive systems.
The research in our group targets two classes of problems: automating high-variation tasks in complex and dynamic environments (such as inspection, repair and maintenance, and advanced manufacturing) and building the intelligence behind adaptive, resilient autonomous systems for extreme and unstructured environments, notably space.
Robust autonomy is achieved through advanced perception coupled with high-fidelity digital models that mirror the physical world, enabling embodied and physically grounded intelligence. Our research spans spatial and agentic intelligence, interaction-aware and actionable world models, and evolving digital twins. 

![Spatial AI](https://github.com/p4mars/P4MARS.github.io/blob/main/images/spatial-ai-2526Q4.jpg)

{% include section.html %}

## News

{% include list.html data="events" component="event" lookup="ICRA26"%}
{%
  include button.html
  link="events"
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
