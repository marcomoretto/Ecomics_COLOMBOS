# Ecomics_COLOMBOS
### A collection of Jupyter notebooks to compare the Ecomics and COLOMBOS transcriptomic datasets

COLOMBOS (https://doi.org/10.1093/nar/gkv1251) and Ecomics (https://dx.doi.org/10.1038%2Fncomms13090) are two datasets that integrate public gene expression data using two different approaches. COLOMBOS integration strategy is based on *fold-changes* (in the form of log-ratios), where each gene measurement does not represent the expression value in a single sample or condition, but a *change* in gene expression comparing a *test* condition to a *reference* condition (a *contrast*), thus is a *relative* measurement. The Ecomics integration strategy instead, employs a normalization method to represent expression levels in *absolute-scale*.

The following collection of Jupyter notebooks tries to add some further insights on the peculiarities of the two distinct approaches. Both datasets are publicly available and thus all the following analysis should be easily reproducible. The purpose of the following comparison is to allow for a more informed decision on which dataset to pick depending on the task to be done.

Data availability:
COLOMBOS: http://colombos.fmach.it/cws_data/compendium_data/ecoli_compendium_data.zip
Ecomics: https://www.dropbox.com/sh/lqzyd6dzmg1a2c4/AADHqUbNXzKyya_tNQOHN__Wa?dl=0
Ecomics meta-data: https://www.ncbi.nlm.nih.gov/pmc/articles/PMC5059772/bin/ncomms13090-s2.xlsx (sheet Transcriptome)
