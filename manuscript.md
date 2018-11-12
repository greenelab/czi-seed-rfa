---
author-meta:
- Loyal A. Goff
- Casey S. Greene
- Stephanie C. Hicks
- Rob Patro
- Elana J. Fertig
- Michael I. Love
date-meta: '2018-11-12'
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
([permalink](https://greenelab.github.io/czi-seed-rfa/v/9cef2522923b869c6261db9d19bc5041577f58b1/))
was automatically generated
from [greenelab/czi-seed-rfa@9cef252](https://github.com/greenelab/czi-seed-rfa/tree/9cef2522923b869c6261db9d19bc5041577f58b1)
on November 12, 2018.
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
* ProjectR & scCoGAPS: [@cJPxOJMp]
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
5. Tom Hampton is Director of Bioinformatic Training for two program projects at the Geisel School of Medicine at Dartmouth. In that role, he has a long collaboration with co-PI Casey Greene, with whom he has collaborated in the development of short courses taught at Mount Desert Island Biological Laboratory and at Dartmouth. Dr Hampton’s  bioinformatic research is focused on using data from multiple independent studies to identify concordant patterns of gene express in response to stressors such as infection and environmental stress.
6. Michael Love is an Assistant Professor of Biostatistics and Genetics at the University of North Carolina at Chapel Hill. He is a leading developer of statistical software for RNA-seq analysis in the Bioconductor Project, maintaining the widely used DESeq2 [@w9AOzBMw] and tximport [@9CN5KEFo] packages. He is a close collaborator with Dr. Rob Patro on bias-aware estimation of transcript abundance from RNA-seq and estimation of uncertainty during transcript quantification [@vrqQcFyx]. Dr. Love will work with co-PIs to disseminate versioned reference cell type catalogs through widely used frameworks for genomic data analysis including R/Bioconductor and Python.
7. Rob Patro is an Assistant Professor of Computer Science at Stony Brook University.  He leads the COMBINE-lab, that [develops and maintains numerous open-source genomics tools and methods](https://github.com/COMBINE-lab).  He is the primary developer of the popular transcript quantification tools Sailfish [@RIPzCufe] and Salmon [@vrqQcFyx], having collaborated closely with Dr. Love on the latter. He and Dr. Love are actively collaborating on improved methods for transcript quantification, differential testing, and also on reproducible analysis via [tximeta](https://github.com/mikelove/tximeta). He has recently been focused on developing improved methods for gene-level quantification from tagged-end single-cell RNA-seq data, as implemented in the alevin tool [@FPpU83vH]. Dr. Patro will worth with co-PIs to develop improved single-cell quantification tools that can account for gene-ambiguous reads and provide uncertainty information about the quantification estimates (base enabling technologies) --- which is important for accurate and robust creation of reduced-dimensionality latent spaces.  He will also work with the co-PIs to develop efficient algorithms and data structures, and robust implementations, to enable efficient expression search over low-dimensional representations of HCA data (Aim 1).


## Proposal Body (2000 words)

The Human Cell Atlas (HCA) provides unprecedented characterization of molecular phenotypes 
across individuals, tissues and disease states -- resolving differences to the level of 
individual cells. This dataset provides an extraordinary opportunity for scientific advancement, enabled by new tools to rapidly query, characterize, and analyze these intrinsically 
high-dimensional data. To facilitate this, our seed network proposes to compress HCA data into fewer dimensions 
that preserve the important attributes of the original high dimensional data and yield
interpretable, searchable features. For transcriptomic data, compressing on the gene 
dimension is most attractive: it can be applied to single samples, and genes often provide 
information about other co-regulated genes or cellular attributes. We hypothesize that building an ensemble of low dimensional representations across latent space methods will provide a  
reduced dimensional space that captures biological sources of variability and is robust to measurement noise. Our seed network will 
incorporate biologists and computer scientists from five leading academic institutions who will work together to create foundational technologies 
and educational opportunities that promote effective interpretation of low dimensional representations of HCA data. We will continue our active collaborations with other
members of the broader HCA network to integrate state of the art latent space tools, portals, and annotations to enable biological utilization of HCA data through latent spaces.  

## Scientific Goals

We will create low-dimensional representations that provide search and catalog capabilities 
for the HCA. Given both the scale of data, and the inherent complexity of biological 
systems, we believe these approaches are crucial to the long term success of the HCA. Our 
**__central hypothesis__** is that these approaches will enable faster algorithms while 
reducing the influence of technical noise. We propose to advance **__base enabling 
technologies__** for low-dimensional representations.

First, we will identify techniques that learn interpretable, biologically-aligned 
representations. We will consider both linear and non-linear techniques as each may identify 
distinct components of biological systems. For linear techniques, we rely on our Bayesian,
non-negative matrix factorization method scCoGAPS [@6i1NIkNx,@cJPxOJMp]
(PIs Fertig & Goff). This technique learns biologically relevant features across contexts 
and data modalities [@wkhRfjyx,@1GkdWBzqU,@uInnOMwX,@1DZRsfkoC,@6i1NIkNx], 
including notably the HPN DREAM8 challenge [@qpg6x7P4]. This technique is 
specifically selected as a base enabling technnology because its error distribution can 
naturally account for measurement-specific technical variation 
[@5Cj8i4Xu] and its prior distributions for different feature 
quantifications or spatial information. For non-linear needs, neural networks with multiple 
layers provide a complementary path to low-dimensional representations 
[@5CsWRjfp] (PI Greene) that model these diverse features of HCA data. We will 
make use of substantial progress that has already been made in both linear and non-linear 
techniques (e.g.,
[@vpa3pNZU,@XjfRUvN5,@TkR5VPF7,@V3nGUaio,@eMe9qeSH,@1GR3FIJMG,@GC2u23Xj,@OekvE5up]).
and rigorously evaluate emerging methods into our search and catalog tools. We will extend 
transfer learning methods, including ProjectR [@cJPxOJMp] (PIs Goff & Fertig) to 
enable rapid integration, interpretation, and annotation of learned latent spaces. The 
latent space team from the HCA collaborative networks RFA (including PIs Fertig, Goff,
Greene, and Patro) is establishing common definitions and requirements for latent spaces 
for the HCA, as well as standardized output formats for low-dimensional representations from 
distinct classes of methods.

Second, we will improve techniques for fast and accurate quantification. Existing approaches 
for scRNA-seq data using tagged-end end protocols (e.g. 10x Chromium, drop-Seq, inDrop, 
etc.) do not account for reads mapping between multiple genes. This affects approximately 
15-25% of the reads generated in a typical experiment, reducing quantification accuracy, and 
leading to systematic biases in gene expression estimates [@FPpU83vH]. To address 
this, we will build on our recently developed quantification method for tagged-end data that 
accounts for reads mapping to multiple genomic loci in a principled and consistent way 
[@FPpU83vH] (PI Patro), and extend this into a production quality tool for 
scRNA-Seq preprocessing. Our tool will support: 1. Exploration of alternative models for 
Unique Molecular Identifier (UMI) resolution. 2. Development of new approaches for quality 
control and filtering using the UMI-resolution graph. 3. Creation of a compressed and 
indexible data structure for the UMI-resolution graph to enable direct access, query, and 
fast search prior to secondary analysis.

We will implement these base enabling technologies and methods for search,
analysis, and latent space transformations as freely available, open source software tools. 
We will additionally develop platform-agnostic input and output data formats and standards 
for latent space representations of the HCA data to maximize interoperability. The software 
tools produced will be fast, scalable, and memory-efficient by leveraging the available 
assets and expertises of the R/Bioconductor project (PIs Hicks & Love) as well as the 
broader HCA community.

By using and extending our base enabling technologies, we will provide three principle 
tools and resources for the HCA. These include 1) software to enable fast and accurate 
search and annotation using low-dimensional representations of cellular features, 2) a 
versioned and annotated catalog of latent spaces corresponding to signatures of cell types, 
states, and biological attributes across the the HCA, and 3) short course and educational 
materials that will increase the use and impact of low-dimensional representations and the 
HCA in general.

### Aim 1

*Rationale:* The HCA provides a reference atlas to human cell types, states, and the 
biological processes in which they engage. The utility of the reference therefore requires 
that one can easily compare references to each other, or a new sample to the compendium of 
reference samples. Low-dimensional representations, because they compress the space, provide 
the building blocks for search approaches that can be practically applied across very large 
datasets such as the HCA. *We propose to develop algorithms and software for efficient 
search over the HCA using low-dimensional representations.*

The primary approach to search in low-dimensional spaces is straightforward: one
must create an appropriate low-dimensional representation and identify distance functions 
that enable biologically meaningful comparisons. Ideal low-dimensional representations are 
predicted to be much faster to search, and potentially more biologically relevant, as noise 
can be removed. In this aim, we will evaluate novel low-dimensional representations to 
identify those with optimal qualities of compression, noise reduction, and retention of 
biologically meangful features. Current scRNA-Seq approaches require investigators to 
perform gene-level quantification on the entirety of a new sample. We aim to enable search 
during sample preprocessing, prior to gene-level quantification. This will enable in-line 
annotation of cell types and states and identification of novel features as samples are 
being processed. We will implement and evaluate techniques to learn and transfer shared 
low-dimensional representations between the UMI-resolution graph and quantified samples, so 
that samples where either component is available can be used for search and annotation 
**[CASEY ADD SHARED LATENT SPACE REF]**. These UMI-graphs will be embedded in the prior of 
scCoGAPS and architecture of non-linear latent space techniques. **[Do we need this line? 
It's a bit more specific than the rest of the paragraph -LAG]** 
**[I think we need something to link in how this fits to the latent space methods -- maybe not so specific, but something that ties it back beyond preprocessing - EJF]**

Similarly to the approach by which comparisons to a reference genomes can identify specific 
differences in a genome of interest, we will use low-dimensional representations from latent 
spaces to define a reference transcriptome map (the HCA), and use this to quantify 
differences in target transcriptome maps from new samples of interest. We will leverage 
common low-dimensional representations and cell-to-cell correlation structure both within 
and across transcriptome maps from Aim 2 to define this reference. Quantifying the 
differences between samples characterized at the single-cell level reveals population or 
individual level differences. 
**[<-- I'm not sure what this sentence means.  Please clarify.  - LAG]**
**[My take is that it means if we have an average from the catalogue we've built for a cell type or state, that deviations in particular samples could yield context-specific differences, not sure how to reword - EJF]**
Comparison of scRNA-seq maps from individuals with a particular phenotype 
to the HCA reference, which is computationally infeasible from the large scale of HCA data, 
becomes tractable in these low dimensional spaces. We (PI Hicks) have extensive
experience dealing with the distributions of cell expression within and between
individuals [@13owodqhx], which will be critical for defining an appropriate
metric to compare references in latent spaces. We plan to implement and evaluate 
linear mixed models to account for the correlation structure within and between 
transcriptome maps. This statistical method will be fast, memory-efficient and will 
be scalable to billions of cells using low-dimensional representations.

### Aim 2

*Rationale:* Biological systems are comprised of diverse cell types and states with
overlapping molecular phenotypes. Furthermore, biological processes are often reused with
modifications across cell types. Low-dimensional representations can identify these shared 
features, independent of total distance between cells in gene expression space, across large 
collections of data including the HCA. We will evaluate and select methods that define 
latent spaces that reflect discrete biological processes or cellular features. These latent 
spaces can be shared across different biological systems and can reveal context-specific 
divergence such as pathogenic differences in disease. *We propose to establish a central 
catalog of cell types, states, and biological processes derived from low-dimensional 
representations of the HCA.*

Establishing a catalog of cellular features using low-dimensional representations can 
reduce noise and aid in biological interpretability. However, there are currently no 
standardized, quantitative metrics to determine the extent to which low-dimensional 
representations capture generalizable biological features. We have developed new transfer 
learning methods to quantify the extent to which latent space representations from one
set of training data are represented in another [@cJPxOJMp,@1GtRgPRxn,@1GtRgPRxn] 
(PIs Greene, Goff & Fertig).
These provide a strong foundation to compare different low-dimensional representations
and techniques for learning and transferring knowledge between them [**<-- didn't understand
what was here before too well, please make sure I didn't muck with the meaning too much.**]
Generalizable representations should transfer across datasets of related biological 
contexts, while representations of noise will not. In addition, we have found that combining 
multiple representations can better capture biological processes across scales 
[@Hlprh8TG], and that representations across scales capture distinct, 
valid biological signatures [@5Cj8i4Xu]. Therefore, we will 
establish a catalog consisting of low-dimensional features learned across both 
linear and non-linear methods from our base enabling technologies and proposed
extensions in Aim 1.

We will package and version low-dimensional representations and annotate these 
representations based on their corresponding celluar features (e.g. cell type, tissue, 
biological process) and deliver these as structured data objects in Bioconductor as well as 
platform-agnostic data formats. Where applicable, we will leverage the computational tools 
previously developed by Bioconductor for single-cell data access to the HCA, data 
representation (`SingleCellExperiment`, `beachmat`, `LinearEmbeddingMatrix`, `DelayedArray`, 
`HDF5Array` and `rhdf5`) and data assessment and amelioration of data quality (`scater`, 
`scran`, `DropletUtils`). We are core package developers and 
power users of Bioconductor (PIs Hicks and Love) and will support on-the-fly downloading of 
these materials via the *AnnotationHub* framework. To enable reproducible research 
leveraging HCA, we will implement a content-based versioning system, 
which identifies versions of the reference cell type catalog by the gene weights and transcript nucleotide 
sequences using a hash function. We (PIs Love and Patro) previously developed hash-based versioning and provenance
detection framework for bulk RNA-seq that supports reproducible 
computational analyses and has proven to be successful [@1FQ0kp4Dj]. 
Our versioning and dissemination of reference cell type catalogs
will help to avoid scenarios where researchers report on matches to a certain cell type in 
HCA without precisely defining which definition of that cell type. We will develop 
*F1000Research* workflows demonstrating how HCA-defined reference cell types and tools 
developed in this RFA can be used within a typical genomic data analysis. This catalogue 
will be used as the basis of defining the references for cell type and state, or 
individual-specific differences with the linear models proposed in Aim 1.

### Aim 3

*Rationale:* Low-dimensional representations of scRNA-seq and HCA data make tasks faster and 
provide interpretable summaries of complex high-dimensional cellular features. The HCA 
data-associated methods and workflows will be valuable to many biomedical fields, but their 
use will require an understanding of basic bioinformatics, scRNA-Seq, and how the tools 
being developed work. Furthermore, researchers will need exposure to the conceptual basis of 
low-dimensional interpretations of biological systems. This aim addresses these needs in 
three ways.

First, we will develop a  bioinformatic training program for biologists at all levels, 
including those with no experience in bioinformatics. Lecture materials will be extended 
from existing materials from previous bioinformatic courses we (PI Hampton) have run at 
Mount Desert Island Biological Laboratory, the University of Birmingham, UK, and Geisel 
School of Medicine at Dartmouth since 2009. These courses have trained over 400 scientists 
in basic bioinformatics and always achieve approval ratings of over 90%.  We believe part of 
the success of these learning experiences has to do with our instructional paradigm, which 
includes a very challenging course project coupled with one-on-one support from instructors. 
We will develop a new curriculum specifically tailored to HCA that incorporates: 1) didactic 
course material on single cell gene expression profiling (PI Goff), 2) 
machine learning methods (PI Greene), 4) statistics for genomics (PIs Fertig and Hicks), 4) search and analysis in low-dimensional 
representations, and 5) tools developed by our group in response to this RFA.

Second, the short course will train not only students, but also instructors. Our one-on-one 
approach to course projects will require a high instructor-to-student ratio. We will 
therefore recruit former participants of this class to return in subsequent years, first as 
teaching assistants, and later as module presenters. We have found that course alumni are 
eager to improve their teaching resumes, that they learn the material in a new way as they 
begin to teach it, and that they are an invaluable resource in understanding how to improve 
the course over time. Part of our strategy is to support this community, which includes many 
people who will drive the next wave of innovation. All of our course materials will be 
freely available, enabling course participants to bring what they learned home with them. A 
capstone session will be included in which we will provide suggestions about how the 
materials presented in the course can be incorporated into existing course curricula. Course 
faculty will be available to assist with integration effort after the course. Finally, the short course will facilitate scientific collaborations 
by engaging participants in utilizing these tools for collaborative research efforts.

**[I feel like we are missing a concluding summary of broader impacts to pull this together - could be a brief bulleted summary of tools required by app as Andrew suggested - EJF]**



## References {.page_break_before}

<!-- Explicitly insert bibliography here -->
<div id="refs"></div>
