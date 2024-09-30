# FLX-MetaDE
Meta Analysis of Fluoxetine SSRI Treatment in High Throughput Sequence Data

This repository contains the following key files:

MetaDE_Flx_LoadData.Rmd -  R markdown (RMD) file, used to process individual differential expression and gene set enrichment analysis (GSEA) outputs [FLX_datasets directory] into MetaDE analysis inputs [Input RDS]

MetaDE_Flx.Rmd - RMD file, used to analyze groups of datasets [Input RDS] produce meta analysis outputs [MetaDE RDS] and generate figures [Figures]

This repository contains the following directories

FLX RMD - RMD files for the differential expression and gene set enrichment analyses for each GEO data set series (GSE)

FLX_datasets - Differential expression and gene set enrichment analysis (GSEA) r objects saved in the .rds file format

Input RDS - Data tables combining the diffential expression and GSEA outputs into different analysis groups to use as inputs for MetaDE saved in the .rds file format

MetaDE RDS - MetaDE output files (Fisher and Maximum-p statistics) for each analysis group saved in the .rds file format

Figures - Image files of figures generated from MetaDE analysis for each analysis group

Additional_Figure_RMD - Additional RMD files used to generate figures

