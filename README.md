# datasets

ferme_pekes_subset_subsampled.tar.gz:

* Fastq files of the ferme pekes project, only participants 1-30.
* Subsampled to 1,000 read pairs per sample.

bac120_ssu_reps_r220_dada2_V4_no-sp.fna.gz:

* V4 sequences extracted from the GTDB 16S reference database with representative sequences of species (release RS220).
* Formatted for the dada2 R package.
* Sequences from "sp-species" have been removed.
* Sequences with more than two consecutive uncalled bases have been removed. 
