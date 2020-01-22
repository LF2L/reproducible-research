---
layout: slides
title: PPT
author: Fabio
permalink: "/PPT/"
image-path: "/assets/figures/"
description: A presentation slide for how to use reveal.js in Jekyll
theme: white
transition: none
---

<style>
.container{
    display: flex;
}
.col{
    flex: 1;
}

.reveal {
  font-family: "Source Sans Pro", Helvetica, sans-serif;
  font-size: 30px;
  font-weight: normal;
  color: #222; }


.reveal p {
    text-align: left;
  }
.reveal ul {
    display: block;
  }
.reveal ol {
    display: block;
  }  


</style>

<section data-markdown data-separator="---">
<script type="text/template">


## Reproducible Research module
#### Innovation, Development & Research

<img height="400px" class="plain" src="{{ site.baseurl | append:page.image-path | append: 'Phd-comics.gif' }}">

##### Fabio A. Cruz Sanchez
##### Giovanny Arbelaez
##### Mauricio Camargo

<div class="cf"></div>

Ecole Nationale Supérieur en Génie des Systèmes et de l'Innovation (ENSGSI) 

Équipe de Recherche sur les Processus Innovatifs (ERPI)

<img height="100px" class="plain" src="https://erpi.univ-lorraine.fr/assets/images/logo-ERPI.svg">


---

# Main goal

- Understand the importance of the *replication principle* in research
- Create a first dynamic document using a *Literate programming approach*


---
## Music Vs. Research

<div class="container">
  <div class="col">
    <img height="600px" class="plain" src="{{ site.baseurl | append:page.image-path | append: 'Musica.jpeg' }}">

  </div>

<div class="col">
  <img height="600px" class="plain" src="{{ site.baseurl | append:page.image-path | append: 'Paper.png' }}">
</div>

</div>

---

# The paper Pipeline

<img height="120%" class="plain" src="{{ site.baseurl | append:page.image-path | append: 'Article-pipeline-1.png' }}">



---

# The paper Pipeline


<img height="120%" class="plain" src="{{ site.baseurl | append:page.image-path | append: 'Article-pipeline-2.png' }}">

Describe in detail this section...

---

## Reproducibility and Replicability

**Reproducibility**: 

Refers to the ability of a researcher to duplicate the results of a prior study using the same materials as were used by the original researcher (Goodman, Fanelli, and Ioannidis 2016).

- Focuses on the validity of the data analysis
- "Can we trust this analysis?"


<small>- Goodman, Steven N., Daniele Fanelli, and John P. A. Ioannidis. 2016. “What Does Research Reproducibility Mean?” Science Translational Medicine 8 (341): 341ps12–341ps12. https://doi.org/10.1126/scitranslmed.aaf5027.
</small>

---
## Reproducibility and Replicability

Replicability: 

This is the act of repeating an entire study, independently of the original investigator without the use of original data (but generally using the same methods).


- Important for policymakers and regulatory decisions


---


## Why do we need Reproducible Research?

- Avoid misconduct such as fraudulent data and plagiarism
- Data-intensive research (e.g Big data research)
- Distributed research







---
## Replication Vs. Reproducibility

Two key principles: 

- Literate programming for enabling reproducibilty
- Version control for enhancing transparency


---
## Literate programming for enabling reproducibilty

*Literate programming refers to the use of a computing environment for authoring documents that contain a mix of natural (eg. English) and computer (eg. R) languages (Schulte et al. 2012)*


<small> Schulte, Eric, Dan Davison, Thomas Dye, and Carsten Dominik. 2012. “A Multi-Language Computing Environment for Literate Programming and Reproducible Research.” Journal of Statistical Software 46 (1): 1–24. https://doi.org/10.18637/jss.v046.i03.</small




--- 

### What is R/RStudio?

- R is a statistical programming language
- RStudio is a convenient interface for R (an integrated development environment, IDE)
- At its simplest:<sup>➥</sup>
- R is like a car’s engine
 - RStudio is like a car’s dashboard

<img width="100%" src="{{ site.baseurl | append:page.image-path | append: 'engine-dashboard.png' }}">

➥ Source: [Modern Dive](https://moderndive.com/)


---

# Summary

- Reproducible research is important as a **minimum standard**, particularly for studies that are difficult to replicate
- Infrastructure is needed for creating and distributing reproducible documents, beyond what is currently available
- There is a growing number of tools for creating reproducible documents
---






</script>
</section>
