---
author-meta:
- Loyal A. Goff
- Casey S. Greene
- Stephanie C. Hicks
- Rob Patro
- Elana J. Fertig
- Michael I. Love
date-meta: '2018-11-04'
keywords:
- dimensionality reduction
- search
- transformation
- reference
- cell types
- single cell
- Human Cell Atlas
lang: en-US
title: Practical search and analysis with low-dimensional representations of the HCA
...






<small><em>
This manuscript
([permalink](https://greenelab.github.io/czi-seed-rfa/v/fd3b764168fe0e39ca17c01d81a3c506e299bfe1/))
was automatically generated
from [greenelab/czi-seed-rfa@fd3b764](https://github.com/greenelab/czi-seed-rfa/tree/fd3b764168fe0e39ca17c01d81a3c506e299bfe1)
on November 4, 2018.
</em></small>

## Authors



+ **Loyal A. Goff**<br>
    ![ORCID icon](images/orcid.svg){height="13px" width="13px"}
    [0000-0003-2875-451X](https://orcid.org/0000-0003-2875-451X)
    · ![GitHub icon](images/github.svg){height="13px" width="13px"}
    [loyale](https://github.com/loyale)
    · ![Twitter icon](images/twitter.svg){height="13px" width="13px"}
    [loyalgoff](https://twitter.com/loyalgoff)<br>
  <small>
     Solomon H. Snyder Department of Neuroscience, Johns Hopkins University School of Medicine; Kavli Neurodiscovery Institute, Johns Hopkins University; McKusick-Nathans Institute of Genetic Medicine, Johns Hopkins University School of Medicine
  </small>

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

+ **Rob Patro**<br>
    ![ORCID icon](images/orcid.svg){height="13px" width="13px"}
    [0000-0001-8463-1675](https://orcid.org/0000-0001-8463-1675)
    · ![GitHub icon](images/github.svg){height="13px" width="13px"}
    [rob-p](https://github.com/rob-p)<br>
  <small>
     Department of Computer Science, Stony Brook University
  </small>

+ **Elana J. Fertig**<br>
    ![ORCID icon](images/orcid.svg){height="13px" width="13px"}
    [0000-0003-3204-342X](https://orcid.org/0000-0003-3204-342X)
    · ![GitHub icon](images/github.svg){height="13px" width="13px"}
    [ejfertig](https://github.com/ejfertig)
    · ![Twitter icon](images/twitter.svg){height="13px" width="13px"}
    [FertigLab](https://twitter.com/FertigLab)<br>
  <small>
     Department of Oncology, Sidney Kimmel Comprehensive Cancer Center, School of Medicine, Johns Hopkins University; Department of Applied Mathematics and Statistics, Whiting School of Engineering, Johns Hopkins University
  </small>

+ **Michael I. Love**<br>
    ![ORCID icon](images/orcid.svg){height="13px" width="13px"}
    [0000-0001-8401-0545](https://orcid.org/0000-0001-8401-0545)
    · ![GitHub icon](images/github.svg){height="13px" width="13px"}
    [mikelove](https://github.com/mikelove)
    · ![Twitter icon](images/twitter.svg){height="13px" width="13px"}
    [mikelove](https://twitter.com/mikelove)<br>
  <small>
     Department of Biostatistics, University of North Carolina at Chapel Hill; Department of Genetics, University of North Carolina at Chapel Hill
  </small>



## Abstract {.page_break_before}

**Instructions**: Describe your collaborative project, highlighting key achievements of the project; limited to 250 words.


## Five Key References

* Hicks refs: [@DJaucmAA]
* projectR & scCoGAPS: [@cJPxOJMp]
* Alevin: [@FPpU83vH]


## Project Team

### PI information

1. Loyal Goff (Submitter)

    * Title: Assistant Professor
    * Degrees: PhD
    * Type of organization: Academic
    * Tax ID: 52-0595110 (JHU)
    * Email: loyalgoff@jhmi.edu

2. Stephanie Hicks

    * Title: Assistant Professor
    * Degrees: PhD
    * Type of organization: Academic
    * Tax ID: 52-0595110 (JHU)
    * Email: shicks19@jhu.edu

3. Elana Fertig

    * Title: Associate Professor
    * Degrees: PhD
    * Type of organization: Academic
    * Tax ID: 52-0595110 (JHU)
    * Email: ejfertig@jhmi.edu

4. Casey Greene

    * Title: Assistant Professor
    * Degrees: PhD
    * Type of organization: Academic
    * Tax ID: 23-1352685 (UPenn)
    * Email: greenescientist@gmail.com

5. Tom Hampton

    * Title: Senior Bioinformatics Analyst
    * Degrees: PhD
    * Type of organization: Academic
    * Tax ID: 02-0222111 (Dartmouth)
    * Email: Thomas.H.Hampton@dartmouth.edu

6. Michael Love

    * Title: Assistant Professor
    * Degrees: Dr. rer. nat.
    * Type of organization: Academic
    * Tax ID: 56-6001393 (UNC)
    * Email: milove@email.unc.edu

7. Rob Patro
    * Title: Assistant Professor
    * Degrees: PhD
    * Type of Organization: Academic
    * Tax ID: 16-1514621 (Stony Brook)
    * Email: rob.patro@cs.stonybrook.edu


### Description (750 words TOTAL)

1. Loyal Goff
2. Stephanie C. Hicks is an Assistant Professor of Biostatistics at the Johns Hopkins Bloomberg School of Public Health. She is an expert in statistical methodology with a strong track record in processing and analyzing single-cell genomics data, including extensive experience developing fast, memory-efficient R/Bioconductor software to remove systematic and technical biases from scRNA-seq data [@DJaucmAA]. Dr. Hicks will work together with Co-PIs to implement fast search algorithms in latent spaces (Aim 1) and to implement the methods developed into fast, scalable, and memory-efficient R/Bioconductor software packages (Aim 3).
3. Elana Fertig is an Associate Professor of Oncology and Applied Mathematics and Statistics at Johns Hopkins University. She developed of the Bayesian non-negative matrix factorization algorithm CoGAPS [@1DrhKLdVp] for latent space analysis. In collaboration with co-PI Goff, she adapted this tool to scRNA-seq data and developed a new transfer learning framework to relate the low-dimensional features in scRNA-seq data across data modalities, biological conditions, and organisms [@cJPxOJMp]. Dr. Fertig will work with the co-PIs to incorporate the error models from Aim 1 into the latent space representations, dimensionality estimation, and biological assessment metrics in Aim 2. She is developing standardized language for latent space representation in collaboration with co-PIs Goff and Greene [@Sn52lYwa] that will provide a strong foundation for standardization of these approaches across different unsupervised learning tools.
4. Casey Greene
5. Tom Hampton
6. Michael Love is an Assistant Professor of Biostatistics and Genetics at the University of North Carolina at Chapel Hill. He is a leading developer of statistical software for RNA-seq analysis in the Bioconductor Project, maintaining the widely used DESeq2 [@w9AOzBMw] and tximport [@9CN5KEFo] packages. He is a close collaborator with Dr. Rob Patro on bias-aware estimation of transcript abundance from RNA-seq and estimation of uncertainty during transcript quantification [@vrqQcFyx]. Dr. Love will work with co-PIs to disseminate versioned reference cell type catalogs through widely used frameworks for genomic data analysis including R/Bioconductor and Python.
7. Rob Patro



## Proposal Body (2000 words)

The Human Cell Atlas (HCA) provides unprecedented characterization of the
molecular states of each cell across tissues, organisms, and individuals.
Computational techniques that provide the ability to rapidly query,
characterize, and analyze this atlas will accelerate the pace of discovery in
biomedicine. HCA data are high dimensional, but they can often be compressed
into fewer dimensions without a substantial loss of information while yielding
interpretable features. For transcriptomic data, compressing on the gene
dimension is most attractive: it can be applied to single samples, and genes
often provide information about other co-regulated genes. In the best case, the
reduced dimensional space captures biological sources of variability while
ignoring noise and each dimension aligns to interpretable biological processes.

Our seed network aims to create low-dimensional representations that provide
search and catalog capabilities for the HCA. The benefit of these approaches
will become particularly pronounced as the number of cells and tissues becomes
large. Our **__central hypothesis__** is that these approaches will enable
faster algorithms while reducing the influence of technical noise. We propose to
advance **__base enabling technologies__** for low-dimensional representations.
We also propose three aims: 1) fast and accurate search for cell, samples, and
pathways; 2) a catalog of cell types and biological processes in low-dimensional
spaces; and 3) educational materials to increase the impact of low-dimensional
representations and the HCA in general.

*The first goal of our base enabling technology work* is to identify techniques
that learn interpretable, biologically-aligned representations. We consider both
linear and non-linear techniques. For linear techiques, we rely on our Bayesian,
non-negative matrix factorization method scCoGAPS
[@6i1NIkNx,@cJPxOJMp] (PI Fertig). This technique learns
biologically relevant features across contexts and data modalities
[@wkhRfjyx,@1GkdWBzqU,@uInnOMwX,@1DZRsfkoC,@6i1NIkNx],
including notably the HPN DREAM8 challenge [@qpg6x7P4]. We will
modify the scCoGAPS uncertainty estimate to account for measurement-specific
technical variation [@5Cj8i4Xu] in the HCA. As spatially
annotated data becomes available, we will extend scCoGAPS to incorporate this.
For non-linear needs, neural networks with multiple layers, provide a
complementary path to low-dimensional representations [@5CsWRjfp] (PI
Greene). We note that many groups are working in this area for both linear and
non-linear techniques (e.g.,
[@vpa3pNZU,@XjfRUvN5,@TkR5VPF7,@V3nGUaio,@eMe9qeSH,@1GR3FIJMG,@GC2u23Xj,@OekvE5up]).
Because of the substantial number of groups developing neural network based
methods, we don't currently plan additional efforts on this front; however, we
will continue to use and rigorously evaluate these methods. We will incorporate
the best performing methods into our search and catalog tools. The latent space
team from the HCA collaborative networks RFA (including PIs Fertig, Goff,
Greene, and Patro) is defining common output formats for low-dimensional
representations from distinct classes of methods.

The *second part of our work on base enabling technologies* is the improvement
of techniques for fast and accurate quantification. Existing approaches for
quantification from scRNA-seq data using tagged-end end protocols (e.g. 10x
Chromium, drop-Seq, inDrop, etc.) have no mechanism for accounting for reads
mapping between multiple genes in the resulting quantification estimates. This
affects approximately 15-25% of the reads in a typical experiment. It reduces
quantification accuracy, and leads to systematic biases in gene expression
estimates that correlate with the size of gene families and gene function
[@FPpU83vH]. We recently developed a quantification method for
tagged-end data that accounts for reads mapping to multiple genomic loci in a
principled and consistent way [**CITE?**].  We will expand on this work by,
building these capabilities into a production quality tool for the processing of
scRNA-seq data. The tool will support: 1. Exploring alternative models for UMI
resolution. 2. Developing new approaches for quality control and filtering using
the UMI-resolution graph. 3. Creating a compressed and indexible data structure
for the UMI-resolution graph to enable direct access, query, and fast search.

We will implement the base enabling technologies and methods for search,
analysis, and transformation into R/Bioconductor and Python frameworks. The
python and R software will use common input and output formats. The software
will be fast, scalable, and memory-efficient because will leverage the
computational tools previously developed by Bioconductor for single-cell data
access to the HCA, data representation (`SingleCellExperiment`, `beachmat`,
`DelayedArray`, `HDF5Array` and `rhdf5`) and data assessment and amelioration of
data quality (`scater`, `scran`, `DropletUtils`).

### Aim 1

*Rationale:* The HCA provides a reference atlas to human cells, cell types, and
the pathways that they express. Scientists will benefit most from the HCA when
they can quickly identify find cells and cell types and compare references to
find differences. Low-dimensional representations, because they compress the
space, provide the building blocks for search approaches that can be practically
applied across very large datasets such as the HCA. *We propose to develop
algorithms and software for efficient search over the HCA using low-dimensional
representations.*

The primary approach to search in low-dimensional spaces is straightforward: one
must create an appropriate low-dimensional representation and identify a
distance function or functions that match what biologists seek. Using the
low-dimensional representation improves speed and can also reduce noise. We will
evaluate representations for their ability to support search and implement the
best performing approach. However, the most obvious approaches require
investigators to perform quantification on the entirety of a new sample and
select cells or cell types that they wish to search for. We also aim to enable
search even before investigators complete quantification. This will allow
software to identify similar tissues or identify cells that are unusual as data
are being collected. We will implement and evaluate techniques to learn shared
low-dimensional representations between the UMI-resolution graph and quantified
samples, so that samples where either component is available can be used for
search **[CASEY ADD SHARED LATENT SPACE REF]**.

Reference genomes allow scientists to identify specific differences between the
reference and genomes of interest. We will use these representations to quantify
differences between a reference transcriptome map (the HCA) and target
transcriptome maps from samples of interest. We will leverage common
low-dimensional representations and cell-to-cell correlation structure both
within and across transcriptome maps. Quantifying the differences between
samples characterized at the single-cell level reveals population or individual
level differences. One could compare ten scRNA-seq maps from individuals with a
particular phenotype to the HCA reference. We (PI Hicks) have extensive
experience dealing with the distributions of cell expression within and between
individuals [@13owodqhx], which will be critical for defining an appropriate
metric. We plan to implement and evaluate linear mixed models to account for the
correlation structure within and between transcriptome maps. This statistical
method will be fast, memory-efficient and will scale to billions of cells
because we will use low-dimensional representations.

### Aim 2

*Rationale:* Biological systems are comprised of diverse cell types with
overlapping molecular phenotypes and biological processes are often reused with
modifications across cell types. Low-dimensional representations can reveal
these fundamental mechanisms across large collections of data including the HCA.
We are evaluating and selecting methods that define basis vectors that reflect
discrete biological processes or features. These basis vectors can be shared
across different biological systems and can reveal context-specific
perturbations such as pathogenic differences in disease. *We propose a central
catalog of cell types and biological processes derived from low-dimensional
representations of the HCA.*

Basing a catalog of cell types and their corresponding processes off of multiple
low-dimensional representations can reduce noise and aid in biological
interpretability. However, there are currently no standardized, quantitative
metrics to determine the extent to which low-dimensional representations capture
generalizable biolobical features. We have developed new transfer learning
methods to quantify the extent to which latent space representations from one
set of training data are represented in another
[@cJPxOJMp,@1GtRgPRxn]. These provide a strong foundation to
compare low-dimensional representations. Generalizable representations should
transfer across datasets of related biological contexts. In addition, We have
found that combining multiple representations can better capture biological
processes across scales [@Hlprh8TG], and that
representations across scales capture distinct, valid signatures
[@5Cj8i4Xu].

We will package and version reference cell types and their corresponding
low-dimensional representations and deliver these as structured data objects in
Bioconductor and Python. Such summaries and annotations have proven widely
successful for the ENCODE, Roadmap Epigenome Mapping, and GTEx projects. We are
core package developers and power users of Bioconductor (PIs Hicks and Love) and
will support on-the-fly downloading of these materials via the *AnnotationHub*
framework. To enable reproducible research leveraging HCA, we will implement a
content-based versioning system, which identifies versions of the reference cell
type catalog by the gene weights and transcript nucleotide sequences using a
hash function. We (PI Love) developed hash-based versioning and provenance
identification and detection framework for bulk RNA-seq that supports
reproducible computational analyses and has proven to be successful
[@1FQ0kp4Dj]. This will help to avoid scenarios where
researchers report on matches to a certain cell type in HCA without precisely
defining which definition of that cell type. We will develop *F1000Research*
workflows demonstrating how HCA-defined reference cell types and tools developed
in this RFA can be used within a typical genomic data analysis.

### Aim 3

*Rationale:* Low-dimensional representations for scRNA-seq and HCA data make
tasks faster and provide interpretable summaries of complex high-dimensional
data. The HCA data associated methods, will be valuable to many biomedical
fields, but their use will require experience with this new toolkit. A scalable
education effort that reaches students at and beyond undergraduate level will be
needed to prepare students and maximize impact. *We propose short-course
training for the HCA, single cell profiling, machine learning methods,
low-dimensional representations, and tools developed by our group in response to
this RFA.*

Our educational program is based on a one-week short course that we (PI Hampton)
have run annually at Mount Desert Island Biological Lab over the last **X TOM
FILL IN** years. The course covers R, gene expression analysis, statistical
interpretation, and introduces machine learning (PI Greene). Attendees rate the
course well and report that they incorporate new knowledge into their research
and teaching. For this grant we will add topics centered on the HCA and increase
the frequency of the course. We will run the course at locations distributed
throughout the US and provide open course materials on GitHub to allow others to
replicate the course. New topics will include:

- Comparison of Bulk and Single-cell Assays and Data
- The Human Cell Atlas Project
- scRNA-seq: Expression Quantification and Cell Type Discovery
- scRNA-seq: Low-dimensional Representations
- scRNA-seq: Search and Analysis in Low-dimensional Representations

We aim to provide a force-multiplier for the HCA and low-dimensional methods as
course attendees transmit what they learn to tens of students each year at their
own institutions. We will run this course on a cost recovery model, but to
maximize the multiplier effect we budget at least *ten scholarships* per
offering to cover the room, board, and tuition of faculty who are primarily
engaged in undergraduate instruction. This will allow faculty who will
disseminate these materials in their own reaching to attend at very low cost. We
will develop a one-week module that can be added in to an undergraduate class on
single-cell profiling and the HCA, which we will distribute via GitHub.
Materials will include recorded videos (intended for a refresher for
instructors), slides, and exercises. We expect that this module will support
faculty who attend with an easy enhancement to any bioinformatics or
computational biology instruction that they are already providing at their
institution.


## References {.page_break_before}

<!-- Explicitly insert bibliography here -->
<div id="refs"></div>
