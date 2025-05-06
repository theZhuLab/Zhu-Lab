---
title: Projects
nav:
  order: 2
  
---

# {% include icon.html icon="fa-solid fa-wrench" %}Projects

The cells we are studying includes those in the immune system (e.g., T and B lymphocytes), cardiovascular system (e.g., platelets and endothelial cells), and the neuronal system (e.g., neurons and astrocytes). Cell surface receptors we are studying includes adhesion receptors (e.g., selectins and integrins), immunoreceptors (e.g., TCR, BCR, PD-1, CD40, etc.), and synaptic receptors (e.g., glutamate delta receptor and neuraxin).

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
