# 16S rRNA statistical analyses for takahē gut microbiota

RStudio Statistical analyses associated with the paper [Gut microbiota of the threatened takahe: biogeographic patterns and conservation implications](https://animalmicrobiome.biomedcentral.com/articles/10.1186/s42523-021-00158-5) published in _Animal Microbiome_ 2022.

Amplicon sequence data (demultiplexed, paired-end reads) were sequenced on the Illumina MiSeq platform at Auckland Genomics Ltd and are available in the NCBI SRA repository Bioproject accession number PRJNA737580.  

***

## General notes

This pipeline utilises amplicon sequence variants (ASVs) produced using the R package [DADA2](https://benjjneb.github.io/dada2/). Please refer to the [publication](https://animalmicrobiome.biomedcentral.com/articles/10.1186/s42523-021-00158-5) for specific parameters employed for this dataset and appropriate references. 

This pipeline also contains modified versions of scripts published by Bodkhe et al. 2019 available [here](https://github.com/rahulnccs/Comparison-of-Small-Gut-and-Whole-Gut-Microbiota-of-First-Degree-Relatives-with-Adult-Celiac-Disease). 
