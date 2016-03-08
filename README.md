# grape_ancestry

Genomic Ancestry Estimation Quantifies Use of Wild Species in Grape Breeding 
Correspondence should be addressed to: Sean Myles, sean.myles@dal.ca
March 7, 2016

Details on how these files were filtered can be found in the Materials and Methods section.

####################################################################

File:
vitis_all_samples_imputed.ped

Description:
Genotype table in PLINK .ped format. Contains genotypes for all individuals used in this study for ancestry estimation. Genotypes were obtained using GbS (HindIII-HF/BfaI, HindIII-HF/MseI)

The PED file is a white-space (space or tab) delimited file: the first six columns are:

Family ID
Individual ID
Paternal ID
Maternal ID
Sex (1=male; 2=female; other=unknown)
Phenotype

Genotypes (biallelic) are column 7 onwards. More information on this file format can be found on the PLINK website: http://pngu.mgh.harvard.edu/~purcell/plink/data.shtml#ped

####################################################################

File:
vitis_all_samples_imputed.map

Description: 
Each line of the .map file describes a single marker and contains 4 columns:

chromosome (1-22, X, Y or 0 if unplaced)
rs# or snp identifier
Genetic distance (morgans)
Base-pair position (bp units)

More information on this file format can be found on the PLINK website: http://pngu.mgh.harvard.edu/~purcell/plink/data.shtml#map

####################################################################

File:
vitis_hybrids_not_imputed.ped
vitis_hybrids_not_imputed.map

Description:
Genotype table in PLINK format. Contains genotypes for hybrid samples only prior to imputation. This file was used to calculate IBS values. 

####################################################################

File:
sample_names.txt

Description: 
IDs of samples used in this study contained in the PLINK files (PLINK_ID) as well as the  ID used in the manuscript and figures (PAPER_ID). 
