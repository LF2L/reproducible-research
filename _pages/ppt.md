---
layout: slides
title: PPT
author: Fabio
permalink: "/PPT/"
image-path: "/assets/figures/"
description: A presentation slide for how to use reveal.js in Jekyll
theme: white
transition: slide
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

</style>

<section data-markdown data-separator="---">
<script type="text/template">


## Reproducible Research module
#### Innovation, Development & Research

- Fabio A. Cruz Sanchez
- Giovanny Arbelaez
- Mauricio Camargo

<div class="cf"></div>

<img height="400px" class="plain" src="{{ site.baseurl | append:page.image-path | append: 'Phd-comics.gif' }}">




Ecole Nationale Supérieur en Génie des Systèmes et de l'Innovation (ENSGSI) - Équipe de Recherche sur les Processus Innovatifs (ERPI)

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

## Replication Vs. Reproducibility

<div class="container">
  <div class="col">
    
**Replication** focuses on the validity of scientific claims.

- "Is this claim true?"
- Important for policymakers and regulatory decisions


    

  </div>

<div class="col">

**Reproducibility**  refers to the ability of a researcher to duplicate the results of a prior study using the same materials as were used by the original researcher (Goodman, Fanelli, and Ioannidis 2016).

- Focuses on the validity of the data analysis
- *"Can we trust this analysis?"*



</div>

---


## Why do we need Reproducible Research?

- Avoid misconduct such as fraudulent data and plagiarism

- Data-intensive research (e.g Big data research)








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

# Who use  Reproducible Research?

**Authors**

   -  Want to make their research reproducible 
   -  Want tools for RR to make their lives easier (or at least not much harder)

**Readers** 

   - Want to reproduce (and perhaps expand upon) interesting findings
   - Want tools for RR to make their lives easier


--- 


# Summary

- Reproducible research is important as a **minimum standard**, partcularly for studies that are difficult to replicate
- Infrastructure is needed for creating and distributing reproducible documents, beyond what is currently available
- There is a growing number of tools for creating reproducible documents
---






</script>
</section>
