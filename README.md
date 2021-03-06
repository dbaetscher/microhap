#### Microhaplotype paper analyses

<!-- README.md is generated from README.Rmd. Please edit that file -->

This is an Rstudio project to accompany the paper, "Microhaplotypes provide increased power from short-read DNA sequences for relationship inference." 


## The data

We begin with filtered haplotype data for 144 kelp rockfish at 165 loci that was generated on a MiSeq instrument with paired-end 150-cycle sequencing and prepared using GT-seq amplicon sequencing (Campbell et al. 2015).

Data were filtered using MICROHAPLOT [this repository](https://github.com/ngthomas/callBayes)  according to the following criteria:

1. 20 reads per haplotype
2. 0.2 allelic ratio

1. `./data/kelp_165_microhaps.rds` is an xz-compressed tibble of genotype data for 144 kelp rockfish. Open it in R with `readRDS()`.


All subsequent analyses start from this file.


2. `./data/full_results_snps_v_mhaps_half_sibs_linked_v_unlinked.rds` contains the data used for investigating linked and unlinked markers, in the simulated expanded dataset.


Included here are data processing steps and the code necessary to make each figure (Figs 1-4).

