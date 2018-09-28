---
author-meta:
- Casey S. Greene
- Jane Roe
date-meta: '2018-09-28'
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
([permalink](https://greenelab.github.io/czi-seed-rfa/v/348e01f786f7e6cdcf6ad7cb8d69ba1a9cbadbcf/))
was automatically generated
from [greenelab/czi-seed-rfa@348e01f](https://github.com/greenelab/czi-seed-rfa/tree/348e01f786f7e6cdcf6ad7cb8d69ba1a9cbadbcf)
on September 28, 2018.
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

+ **Jane Roe**<br>
    ![ORCID icon](images/orcid.svg){height="13px" width="13px"}
    [XXXX-XXXX-XXXX-XXXX](https://orcid.org/XXXX-XXXX-XXXX-XXXX)
    · ![GitHub icon](images/github.svg){height="13px" width="13px"}
    [janeroe](https://github.com/janeroe)<br>
  <small>
     Department of Something, University of Whatever; Department of Whatever, University of Something
  </small>



## Abstract {.page_break_before}






## Project Team

* Elana Fertig
* Loyal Goff
* Casey Greene (Submitter)
* Tom Hampton
* Stephanie Hicks
* Mike Love
* Rob Patro



* Base enabling technologies:
  * Low dimensional representations, ProjectR (Elana, Loyal)
  * New methods published by other groups (scVI, etc -  others)
  * Fast & improved quantification  (Rob)

## Aim 1

* Fast search: (in low dimensions, quantifying differences between case and reference maps, twist: shared latent spaces / k-mers)
  * Stephanie: differences b/w maps
  * Rob: new models for UMI deduplication accounting for transcript-level information
    * Parsimony & likelihood based, integrated with gene-level uncertainty
  * Rob: everything FAST! API for search against HCA reference?
  * Casey & Rob: k-mer / quantified latent spaces

## Aim 2

* Transformation of latent spaces
  * Loyal & Elana: search tool for perturbations / signatures in latent-space(s)
  * Elana: latent space transformations for progression? Consider jawns for semi-supervised learning?
  * Loyal transfer of signatures _between_ tissues

## Aim 3

* Reference Cell types
  * Cell-type summarized expression profiles
  * Versioning & provenance of cell types as the reference dataset changes

* Delivery
  * Training / teaching (scRNAseq, low-dimensional representations, RFA-developed tools)
  * Software hardening/testing
  * Bioconductor integration


## References {.page_break_before}

<!-- Explicitly insert bibliography here -->
<div id="refs"></div>
