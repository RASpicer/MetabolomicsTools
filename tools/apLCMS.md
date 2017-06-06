# apLCMS
Version: 6.2.0

## Website
http://web1.sph.emory.edu/apLCMS/

## Description
This is an R package for the preprocessing of high resolution LC-MS data. It contains functions to reduce noise, identify features, correct for retention time deviation, align features across samples and recover weak-signals from LC-FTMS. First peaks are grouped based on their m/z, using a threshold value which is set using a mixture model. These groups are then split into smaller groups using kernel density functions by their rt and m/z. A run-filter is used to distinguish features from noise. The data are then grouped, with each group tentatively said to contain either one or a few features, with the aim of disentangling features with close m/z and rts. A kernel smoother is first fitted to estimate the number of features and their locations; this can return either a single peak, or if multiple peaks are found a maximisation-expectation (EM) algorithm with pseudo-likelihood is used for estimation. Next a feature table is generated for retention time alignment. Features are first aligned by m/z, using the same strategy as peak picking. A rt threshold value is then found using a model-based search. Pairwise rt differences between all features in a group are found and a triangular density function is to find the threshold. A kernel smoother is then used for rt alignment, using the profile with the most number of features as the template. Grouping is then reperformed. Weak signals from LC-FTMS data can then be recovered. Data is separated into XICs using adaptive binning. A large number of feature measurements are taken from every XIC. XICs are then matched to known metabolites; features mapped to known metabolites are more likely to be real signals. Machine learning techniques are used to find the optimum way of distinguishing between matched and unmatched XICs. Models are compared using cross validation.

## Functionality
- Preprocessing

## Instrument Data Type
- MS/LC-MS/LC-FT-MS

## Approaches
- Untargeted

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
MASS, rgl, mzR, splines, doSNOW, foreach, iterators, snow, ROCR, ROCS, e1071, randomForest, gbm

## Input Formats - Open
mzData, mzML, mzXML, netCDF

## Input Formats - Proprietary
N/A

## Published
2009

## Last Updated
2016

## License
GPL (≥ 2)

## Paper
http://www.ncbi.nlm.nih.gov/pubmed/25005748

## PMID
25005748
