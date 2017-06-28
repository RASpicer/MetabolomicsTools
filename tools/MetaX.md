# MetaX
``` diff
- Deprecated
```
Version: 1.0.3

## Website
http://bioconductor.org/packages/release/bioc/html/metaX.html

## Description
This Bioconductor package provides a pipeline for MS metabolomics data analysis, including preprocessing, normalisation, metabolite identification, statistical analysis and pathway analysis. It will accept either raw data in open formats or already peak picked data as input. Specifically it will import directly from Progenesis QI, XCMS and MetaboAnalyst. If raw data is imported, XCMS is used for peak picking and CAMERA is used for annotation. Data is then filtered - if a feature is found in <50% of QC samples or <20% experimental samples, it is removed. Missing values are then imputed using either min, Bayesian PCA (BPCA), k nearest-neighbour (KNN), missForest or singular value decomposition imputation (SVDImpute). Outliers are removed using expansion of the Hotelling's T2 distribution ellipse. Next normalisation is performed; a number of algorithms are provided - QC-robust spline batch correction (QC-RSC), sum, VSN, probabilistic quotient normalization (PQN), quantiles and robust quantiles. For QC-RSC normalisation there must be pooled QC samples included in the study. Metabolites can be putatively identified using HMDB. Optionally data can be transformed using either log transformation or cube root transformation. Scaling can be performed using pareto, vector or uv scaling. Power analysis and sample size estimation can also be performed. Statistical analysis provided includes: t-test, Mann-Whitney U test, ROC analysis, heatmaps, PCA and PLS-DA. Correlation network analysis can be performed. Metabolite pathway analysis based on IMPaLA can be used for pathway analysis. Functions from package 'caret' can be used for biomarker selection, model creation and performance evaluation. There is currently no paper available for this software.

## Functionality
- Workflow

## Instrument Data Type
- MS/LC-MS

## Approaches
- Metabolomics/Untargeted

## Computer Skills
Advanced

## Software Type
- R Package

## Interface
- Command line interface

## Operating System (OS)
- Unix/Linux
- Mac OS
- Windows

## Language
R

## Dependencies
R (≥ 3.2.0), VennDiagram, pROC, SSPA, methods

## Input Formats - Open
mzXML, netCDF, Peaklist .txt/.csv, Progenesis QI .csv

## Input Formats - Proprietary
N/A

## Published
2015

## Last Updated
2015

## License
LGPL-2

## Paper

## PMID
