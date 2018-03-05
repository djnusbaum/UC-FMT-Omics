# UC-FMT-Omics

This repository contains the .R files used for data analysis in "Gut microbial and metabolomic changes after fecal microbiota transplantation in pediatric ulcerative colitis patients" (2018).

The .R files are divided as follows:
- Alpha Diversity analysis (Figure 1)
- Bray-Curtis Distances/Similarity (Supplementary Figures)
- Microbial Taxonomy using Phyloseq (Figure 2)
- PCoA Analysis of Bray-Curtis Distance Matrices of microbial abundance and metabolomics data (Figure 3), but not including the viromics analysis (Figure 3)
- Viromics Analyis, including PCoA and heatmap (Figure 4)
- Metabolomics Analysis (Figure 5)
- Microbe-Metabolite Correlations (Figure 6)
  
All of these R scripts were written and used in R (version 3.4.1) using RStudio (version 1.0.147) on Mac OS Sierra. The scripts rely on several R packages which are loaded using 'library(package-name)'. Packages can only be loaded in this manner if they have already been installed (i.e. using 'install.packages("package-name")'.
