---
layout: page
title: Helper Prep page
permalink: /helper/
root: ../
---

The role of helpers is defined on the [helper checklist page](https://docs.carpentries.org/topic_folders/hosts_instructors/hosts_instructors_checklist.html#helper-checklist).

The carpentries aims to create an inclusive environment so the [Code of Conduct](https://docs.carpentries.org/topic_folders/policies/code-of-conduct.html) is very important. Please also familiarize yourself with the [key points](https://carpentries.github.io/instructor-training/reference.html) summary of the Carpentries Instructor training to get an idea of the values and strategies we aim to use in Carpentries workshops. Feel free to poke around the rest of the material if you wish, but those key points are what's important in how we work with the learners.  

We maintain a list of common issues that occur during installation as a reference  
that may be useful in preparation and the day of the workshop on the
[Configuration Problems and Solutions wiki page]({{site.swc_github}}/workshop-template/wiki/Configuration-Problems-and-Solutions).

## Syllabus


{% if site.carpentry == "swc" %}
  {% include sc/syllabus.html %}
{% elsif site.carpentry == "dc" %}
  {% include dc/syllabus.html %}
{% elsif site.carpentry == "lc" %}
  {% include lc/syllabus.html %}
{% endif %}


## Schedule

These links contain more details, please skim them.

{% if site.carpentry == "swc" %}
  {% include sc/schedule.html %}
{% elsif site.carpentry == "dc" %}
  {% include dc/schedule.html %}
{% elsif site.carpentry == "lc" %}
  {% include lc/schedule.html %}
{% endif %}
