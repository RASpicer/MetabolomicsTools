# Normalyzer
Version: 1.1.1

## Website
http://normalyzer.immunoprot.lth.se/normalize.php

## Description
This R package is designed to evaluate the suitability of different normalisation methods for a dataset that is normally distributed, in a tab separated file with intensities. 12 different normalisation methods are evaluated: total intensity (TI), median intensity (MedI), average intensity (AI), quantile, NormFinder (NF), variance stabilising normalisation (VSN), robust linear regression (RLR) and LOESS are all global normalisation methods; VSN, RLR and LOESS are also implemented as local methods, where within replicate groups are normalised separately. These different normalisation techniques are then evaluated using many methods including: total intensity, total missing values, pooled intragroup coefficient of variation (PCV) and pearson's and spearman's correlation. The results of these evaluations are then outputted in a report. It is specifically designed for proteomics and DNA microarray and has not been tested for metabolomics by the authors.

## Functionality
- Post-processing

## Instrument Data Type
- Proteomics
- DNA microarray
- Metabolomics

## Approaches
-

## Computer Skills
Advanced

## Software Type
- R Package

## Interface
- Command line Interface

## Operating System (OS)
- Unix/Linux
- Mac OS
- Windows

## Language
R

## Dependencies
R (≥ 3.0.0), vsn, Rcmdr, PerformanceAnalytics, preprocessCore, limma, MASS, abind, e1071, ape, car, raster

## Input Formats - Open
Tab-seperated format

## Input Formats - Proprietary
N/A

## Published
2014

## Last Updated
2015

## License
GPL, Creative Commons

## Paper
http://www.ncbi.nlm.nih.gov/pubmed/24766612

## PMID
24766612
