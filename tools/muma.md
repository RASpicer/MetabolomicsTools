# muma
Version: 1.4.0

## Website
https://cran.r-project.org/web/packages/muma/index.html

## Description
Metabolomics Univariate and Multivariate Analysis (muma - a CRAN package) provides a pipeline for analysis, including preprocessing, statistical analysis and metabolite identification. It also specifically provides a number of analysis tools for NMR data - statistical total correlation spectroscopy (STOCSY) and ratio analysis of NMR spectroscopy (RANSY). Initially a dataset is read and then screened for missing values. Four imputation methods are provided: mean, minimum, half-minimum and zero. Normalisation is then performed for the whole spectra, every variable is transformed into a fraction of the total intensity of the spectrum. A range of scaling techniques are then available: Auto, Pareto, Range, Vast and Medium, with each variable being mean centred before scaling. It provides a variety of both univariate (Welch's T test and Wilcoxon-Mann Whitney) and multivariate (PCA, PLS-DA and OPLS-DA) statistical techniques, as well a method of evaluating the clustering power of PCA. For univariate analysis a decision tree algorithm performs hypothesis tests on a single variable - first Shapiro Wilk's test is used to assess whether the data are normally distributed or not, then either Welch's T test or Wilcoxon-Mann Whitney test are performed. Benjamini-Hochberg multiple testing correction can then be applied. Correlation heatmaps can be created to visualise the data. With NMR data, these heatmaps are referred to as STOCSY and correlations >0.95 indicate a structural relationship between peaks belonging to the same molecule. RANSY is also designed to show the structural relationships between peaks.

## Functionality
- Post-processing
- Statistical Analysis

## Instrument Data Type
- MS
- NMR

## Approaches
-

## Computer Skills
Advanced

## Software Type
Package

## Interface
Command line interface

## Operating System (OS)
- Unix/Linux
- Mac OS
- Windows

## Language
R

## Dependencies
car, pdist, pls, gplots, mvtnorm, robustbase, gtools, bitops, caTools, pcaPP, rrcov

## Input Formats - Open
.csv

## Input Formats - Proprietary
N/A

## Published
2012

## Last Updated
2015

## License
GPL-2

## Paper
http://www.eurekaselect.com/107837/article

## PMID
