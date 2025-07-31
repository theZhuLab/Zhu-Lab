---
layout: default
title: Home
---

# Welcome!

Welcome to the Zhu lab at Georgia Tech. We study single molecular adhesion with force spectroscopy for various cells and disease models. We pioneered in the discovery of force-prolonged bond lifetime, or the "catch bond," using the biomembrane force probe paired with mutation studies and molecular dynamics simulations.

{% include section.html %}

## Highlights

{% capture text %}

Our goal is to understand how mechanical force influences enzyme-linked receptors, such as T cell receptors (TCRs) and B cell receptors (BCRs), to drive effective signal transduction.

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
  image="images/photo.jpg"
  link="research"
  title="Our Research"
  text=text
%}

{% capture text %}

By using tools like biomolecular force probes and molecular tension probes, we study the mechanobiology of single-molecule ligand–receptor interactions and their downstream effects.

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

Meet the people behind the research. Our team brings together scientists at all levels who share a passion for exploring the mechanics of immune signaling and advancing biomedical discovery.

{%
  include button.html
  link="team"
  text="Meet our team"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}

{% endcapture %}

{%
  include feature.html
  image="images/photo.jpg"
  link="team"
  title="Our Team"
  text=text
%}
