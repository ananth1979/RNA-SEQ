# Description

This course provides an introduction to the tools available through the Bioconductor project for manipulating and analysing high-throughput sequencing (HTS) data. We will present a workflow for the analysis RNA-seq data starting from aligned reads in bam format and producing a list of differentially-expressed genes. We will also describe the various resources available through Bioconductor to annotate, visualize and gain biological insight from the differential expression results.

# Prerequisites

- A knowledge of current sequencing technologies, data formats (e.g. fastq and bam) and alignment
- A very basic knowledge of UNIX would be an advantage, but nothing will be assumed and extremely little will be required
- Attendees should be comfortable with using the R statistical language to read and manipulate data, and produce simple graphs.  [Here](https://bioinformatics-core-shared-training.github.io/r-crash-course/) is an R crash course that we suggest looking through before attending this course. 

# Objectives; After this course you should be able to:

- Know what tools are available in Bioconductor for NGS analysis and understand the basic object-types that are utilised
- Given a set of gene identifiers, find out whereabouts in the genome they are located, and vice-versa (i.e. go from genomic coordinates to genes)
- Produce a list of differentially-expressed genes from an RNA-seq experiment

# Aims; During this course you will learn about:

- Quality assessment of raw sequencing reads and aligned reads using R.
- Sources of variation in RNA-seq data
- Differential expression analysis using edgeR and DEseq.
- Annotation resources in Bioconductor.
- Identifying over-represented gene sets amongst a list of differentially-expressed genes
