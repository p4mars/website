---
title: Vacancy
nav:
  order: 5
  tooltip: Musings and miscellany
---

# {% include icon.html icon="fa-solid fa-feather-pointed" %}Vacancy

We are always looking for experienced researchers, passionate perspective and thesis students. If you are interested in working with us, please go through the open posiitons first. If you cannot find suitable positions, you are welcome to initiate an application with a detailed description of topics that you want to work on.

{% include search-box.html %}

{% include tags.html tags=site.tags %}

{% include search-info.html %}


{% include section.html %}
## TA/RA Positions
<details markdown="1">
<summary>Information for interested students</summary>

</details>

{% include list.html data="posts" component="post-excerpt" filter="Array(tags).any? { |t| ['ta-position', 'ra-position'].include?(t) }" %}

## Master Projects
<details markdown="1">
<summary>Information for interested students</summary>

These projects are primarily for students at TU Delft. If you are interested please see below the information that we require from you. Although projects can start anytime, most projects start in the fall and we try to announce them in the spring. We advise interested students to contact us several months before the intended start date.

All of our MSc Thesis + Literature Survey assignments can be extended with a Research Assignment in the same topic. This is an interesting option for students interested in a longer research experience (e.g. if you would like to publish an article during your MSc thesis or do a PhD afterwards). We do not offer separate Research Assignments - only those linked to an MSc thesis project. You may also choose to do an Internship in a company.

If you do not find an interesting project, but you would like to join our group, or your would like to propose your own project, then, send an email to Prof. R. Sabzevari. We can also supervise TUD MSc students in industry or in our partners abroad. 
</details>
<!-- For example in one of our industrial partners or collaborators (e.g., MIT, Stanford, ETH Zurich, Harvard, TUM, etc). Send an email to Prof. J. Alonso-Mora if interested. -->

In the following link you can find a list of available MSc projects. For announced projects, please first contact the daily supervisor to discuss the project.

{% include list.html data="posts" component="post-excerpt" filter="Array(tags).any? { |t| ['master-project'].include?(t) }" %}