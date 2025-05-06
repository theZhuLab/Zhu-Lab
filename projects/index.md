---
title: Projects
nav:
  order: 2
  
---

# {% include icon.html icon="fa-solid fa-wrench" %}Projects

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.
Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.

{% include tags.html tags="publication, resource, website" %}

{% include search-info.html %}

{% include section.html %}

## Featured

{% capture text %}
By using tools like biomolecular force probes and molecular tension probes, we study the mechanobiology of single-molecule ligand–receptor interactions and their downstream effects.
{% endcapture %}

{% include feature.html
  image="assets/images/project1.jpg"
  title="Biomolecular Force Probes"
  text=text
%}

{% capture text %}
We’re engineering tension sensors to reveal how physical forces translate into intracellular signaling during T cell activation.
{% endcapture %}

{% include feature.html
  image="assets/images/project2.jpg"
  title="Tension Probes"
  text=text
  flip=true
%}


{% include list.html component="card" data="projects" filter="group == 'featured'" %}

{% include section.html %}

## More

{% include list.html component="card" data="projects" filter="!group" style="small" %}
