# braineQTLMR_datasets
This repo contains the full datasets (i.e. raw results before filtering for analysis) used in the cross neuro braineQTL MR publication.  

Inventory of files:

## fullWRdata.xlsx

Six worksheets in total:

*instruments* - AMPAD-CMC brain eQTL instruments used in the primary MR analysis.

*WR.results* - Wald Ratio results for the braineQTL versus primary outcome analysis.

*harmonised.results* - harmonised eQTL and primary outcome SNP effects used in MR analysis.

*ENSGtogenemap* - Map used to get from Ensembl gene ID to gene name.

*harmonised.results.table* - Excel pivot table showing the number of harmonised SNPs per primary outcome.

*WR.results.table* - Excel pivot table showing the number of Wald Ratio effects avaiable per primary outcome.

## fullresultstables.xlsx

Six worksheets in total:

*table 1* - Inverse Variance Weighted results (multiple SNP instruments).

*table 2* - Wald Ratio results (single snp instrument) across the primary outcomes tested.

*table 3* - Phenome-wide Wald Ratio results for selected instruments (priortised genes).

*table 4* - Different gene expression effects (eQTL) in AMPAD-CMC for our selected instruments.

*table 5* - Gene expression effects (eQTL) in different brain tissues(GTEx v7) for the selected instruments.

*table 6* - MR results (Wald Ratios) for the eQTLGen instrumented analysis.

*table 7* - Wald Ratio results for the reverse MR conducted in eQTLGen.


## harmonisedeQTLdata_otherstudiescomparison.tar

Tar archive containing rds files (harmonised SNP effects) for the AMP-CMC instrument comparison against other eQTL datasets performed in publication.  Readme file describing the files is available within archive.  

## locusregionalplots.pdf

Regional association plots showing the LD between Wald Ratio effects for different genes in genomic regions where multiple genes were identified in the MR.

## Miami plots for the top MR findings.

*Sz.plot.miami.pdf* - Miami plot showing the MR relationships between gene expression changes and schizophrenia risk.  Chromosomal position is on the x-axis and p-value for the Wald ratio estimate (log10 scaled, directed according to beta) is on the y-axis.  

*pysch.plot.miami.pdf* - Miami plot showing the MR relationships between gene expression changes and the other pyschiatric traits (anorexia, bipolar disorder, major depressive disorder).  Chromosomal position is on the x-axis and p-value for the Wald ratio estimate (log10 scaled, directed according to MR effect) is on the y-axis.  

*neuro.plot1.miami.pdf* - Miami plot showing the MR relationships between gene expression changes and Alzheimer's disease and Parkinson's disease neurological outcomes.  Chromosomal position is on the x-axis and p-value for the Wald ratio estimate (log10 scaled, directed according to MR effect) is on the y-axis.  

*neuro.plot1.miami.pdf* - Miami plot showing the MR relationships between gene expression changes and amyotrophic lateral sclerosis and multiple sclerosis neurological outcomes.  Chromosomal position is on the x-axis and p-value for the Wald ratio estimate (log10 scaled, directed according to MR effect) is on the y-axis.  

## DOI badge

version 1.01 (created 30th April 2020)

[![DOI](https://zenodo.org/badge/260182579.svg)](https://zenodo.org/badge/latestdoi/260182579)




