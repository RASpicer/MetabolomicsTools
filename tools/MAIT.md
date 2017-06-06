# MAIT
Version: 1.8.0

## Website
https://www.bioconductor.org/packages/release/bioc/html/MAIT.html

## Description
Metabolite Automatic Identification Toolkit (MAIT) is a Bioconductor package which uses XCMS for peak detection (matchedFilter or centWave), alignment and filling in missing peaks of LC-MS data. CAMERA is then used for adduct and fragment annotation. At this stage, statistical analysis is then performed (univariate statistical analysis must be performed before the next function will run). If there are two classes of data Student's t-test, Welch's t-test or Mann-Whitney tests can be used; if there are more than two classes ANOVA or Kruskal-Wallis tests can be used. There is also support for adding user defined tests e.g. Fisher's exact test. Multiple testing corrections are also provided, including Bonferroni and FDR. At this stage there is also the option to use peak aggregation techniques that may lead to better feature detection (Fernandez-Albert et al. 2014), through commercial package pagR which provides options such as PCA. 2D- and 3D- PCA plots, heatmaps and boxplots can also be produced. Biotransformation (mass losses) are then detected using a mass allowance window inside the peak group (Breitling et al. 2006). Human biotransformations are already present in MAIT, but user defined biotransformations can also be included. The HMDB (07/09) version is then used for metabolite annotation. PLS-DA and SVM with Kernel and K-NN are provided as validation techniques, which are designed to be used after the rest of the workflow has been completed. Throughout the workflow MAIT class objects are used, improving traceability.

## Functionality
- Workflow

## Instrument Data Type
- MS/LC-MS

## Approaches
-

## Computer Skills
Advanced

## Software Type
R Package

## Interface
Command line interface

## Operating System (OS)
- Unix/Linux
- Mac OS
- Windows

## Language
R

## Dependencies
R (≥ 2.10.0), CAMERA, Rcpp, pls

## Input Formats - Open
mzData, netCDF

## Input Formats - Proprietary
N/A

## Published
2014

## Last Updated
2016

## License
GPL-2.0

## Paper
http://www.ncbi.nlm.nih.gov/pubmed/24642061

## PMID
24642061
