# grape_ancestry

Genomic Ancestry Estimation Quantifies Use of Wild Species in Grape Breeding <br /> 
Correspondence should be addressed to: Sean Myles, sean.myles@dal.ca<br /> 
March 7, 2016<br /> 

Details on how these files were filtered can be found in the Materials and Methods section.<br /> 

####################################################################<br /> 

File:<br /> 
vitis_all_samples_imputed.ped<br /> 

Description:<br /> 
Genotype table in PLINK .ped format. Contains genotypes for all individuals used in this study for ancestry estimation. Genotypes were obtained using GbS (HindIII-HF/BfaI, HindIII-HF/MseI)
<br /> 
The PED file is a white-space (space or tab) delimited file: the first six columns are:<br /> <br /> 

Family ID<br /> 
Individual ID<br /> 
Paternal ID<br /> 
Maternal ID<br /> 
Sex (1=male; 2=female; other=unknown)
Phenotype

Genotypes (biallelic) are column 7 onwards. More information on this file format can be found on the PLINK website:<br />  http://pngu.mgh.harvard.edu/~purcell/plink/data.shtml#ped
<br /> 
####################################################################<br /> 
<br /> 
File:<br /> 
vitis_all_samples_imputed.map<br /> 
<br /> 
Description: <br /> 
Each line of the .map file describes a single marker and contains 4 columns:<br /> 
<br /> <br /> 
chromosome (1-22, X, Y or 0 if unplaced)<br /> 
rs# or snp identifier<br /> 
Genetic distance (morgans)<br /> 
Base-pair position (bp units)<br /> 
<br /> <br /> 
More information on this file format can be found on the PLINK website: http://pngu.mgh.harvard.edu/~purcell/plink/data.shtml#map<br /> 
<br /> 
####################################################################<br /> 
File:<br /> 
vitis_hybrids_not_imputed.ped<br /> 
vitis_hybrids_not_imputed.map<br /> 
<br /> 
Description:<br /> 
Genotype table in PLINK format. Contains genotypes for hybrid samples only prior to imputation. This file was used to calculate IBS values. <br /> 
####################################################################<br /> 
File:<br /> 
sample_names.txt<br /> 
<br /> 
Description:<br />  
IDs of samples used in this study contained in the PLINK files (PLINK_ID) as well as the  ID used in the manuscript and figures (PAPER_ID). <br /> 
