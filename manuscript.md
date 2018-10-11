---
author-meta:
- Casey S. Greene
- Stephanie C. Hicks
- Jane Roe
date-meta: '2018-10-11'
keywords:
- dimensionality reduction
- search
- transformation
- reference
- cell types
- single cell
- Human Cell Atlas
lang: en-US
title: Search for and transformation of human cells and cell types with latent space
  representations
...






<small><em>
This manuscript
([permalink](https://greenelab.github.io/czi-seed-rfa/v/c97109d9aa0c82f6ce113ab47a35af277a7ccbc0/))
was automatically generated
from [greenelab/czi-seed-rfa@c97109d](https://github.com/greenelab/czi-seed-rfa/tree/c97109d9aa0c82f6ce113ab47a35af277a7ccbc0)
on October 11, 2018.
</em></small>

## Authors



+ **Casey S. Greene**<br>
    ![ORCID icon](images/orcid.svg){height="13px" width="13px"}
    [0000-0001-8713-9213](https://orcid.org/0000-0001-8713-9213)
    · ![GitHub icon](images/github.svg){height="13px" width="13px"}
    [cgreene](https://github.com/cgreene)
    · ![Twitter icon](images/twitter.svg){height="13px" width="13px"}
    [greenescientist](https://twitter.com/greenescientist)<br>
  <small>
     Department of Systems Pharmacology and Translational Therapeutics, Perelman School of Medicine, University of Pennsylvania
  </small>

+ **Stephanie C. Hicks**<br>
    ![ORCID icon](images/orcid.svg){height="13px" width="13px"}
    [0000-0002-7858-0231](https://orcid.org/0000-0002-7858-0231)
    · ![GitHub icon](images/github.svg){height="13px" width="13px"}
    [stephaniehicks](https://github.com/stephaniehicks)
    · ![Twitter icon](images/twitter.svg){height="13px" width="13px"}
    [stephaniechicks](https://twitter.com/stephaniechicks)<br>
  <small>
     Department of Biostatistics, Johns Hopkins Bloomberg School of Public Health
  </small>

+ **Jane Roe**<br>
    ![ORCID icon](images/orcid.svg){height="13px" width="13px"}
    [XXXX-XXXX-XXXX-XXXX](https://orcid.org/XXXX-XXXX-XXXX-XXXX)
    · ![GitHub icon](images/github.svg){height="13px" width="13px"}
    [janeroe](https://github.com/janeroe)<br>
  <small>
     Department of Something, University of Whatever; Department of Whatever, University of Something
  </small>



## Abstract {.page_break_before}




## Five Key References


## Project Team (750 words each)

* Elana Fertig
* Loyal Goff
* Casey Greene (Submitter)
* Tom Hampton
* Stephanie Hicks
* Mike Love
* Rob Patro



## Proposal Body (2000 words)

* Base enabling technologies:
  * Low dimensional representations (Elana)
  * New methods published by other groups (scVI, etc -  other groups)
  * Fast & improved quantification  (Rob)
  * Incorporation of uncertainty estimates in low dimensional representations (Rob / Mike / Elana) - note this can be done w/o modification in scCoGAPS

### Aim 1

* Fast search: (in low dimensions, quantifying differences between case and reference maps, twist: shared latent spaces / k-mers)
  * Differences b/w maps (Stephanie)
  * New models for UMI deduplication accounting for transcript-level information (Rob)
    * Parsimony & likelihood based, integrated with gene-level uncertainty
  * Everything FAST! API for search against HCA reference? (Rob)
  * k-mer / quantified latent spaces (Casey / Rob)

### Aim 2

* Eschewing marker genes: Practical exploration of the HCA in latent spaces
  * Search tool for perturbations / signatures in latent-space(s) (Loyal)
    - Differential analysis of latent space usage across contexts
  * Latent space transformations for progression? Consider jawns for semi-supervised learning? (Elana)
  * Transfer learning of signatures _between/across_ tissues (Loyal)

* Reference Cell types
  * Cell-type summarized expression profiles (Mike, Loyal)
    - A 'reference catalog' of reduced dimensional representations
  * Versioning & provenance of cell types / features as the reference dataset changes (Mike)
  * 'Power-user' application of latent-space discovery in novel dataset and projection of HCA into new learned spaces.

### Aim 3

* Delivery
  * Training / teaching (scRNAseq, low-dimensional representations, RFA-developed tools) (Tom)
  * Software hardening/testing (Casey - software eng)
  * Bioconductor integration (Stephanie, Mike)


## References {.page_break_before}

<!-- Explicitly insert bibliography here -->
<div id="refs"></div>
