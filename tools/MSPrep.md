# MSPrep
Version: 1.1

## Website
https://sourceforge.net/projects/msprep/

## Description
This is designed to provide functions that are not incorporated in preprocessing but are required for statistical analysis. It includes missing value imputation, filtering, normalisation and averaging of technical replications. It requires aligned LC-MS intensity data, a dataset linking subject ID to data and a clinical dataset. Firstly technical replicates are summed then averaged; CV is used a user specified threshold as to whether a feature is further included in the analysis. Data can then be filtered by a user-specified cutoff of a feature being required to be present in a certain percentage of samples to be included further. There are then three options for handling missing data: replace with zeros (assuming missing data are true zeroes), replace with one half of the minimum observed value for the compound(assuming missing compounds were below detectable limit) and Bayesian PCA (assuming the compound is present, but failed to be accurately detected). There are then five normalisation options: median, quantile, cross-contribution compensating multiple standard normalisation (CRMN), surrogate variable analysis (SVA) and removal of unwanted variation (RUV).

## Functionality
- Post-Processing

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
pcaMethods (>= 1.24.0), crmn, preprocessCore, sva

## Input Formats - Open
Peaklist

## Input Formats - Proprietary
N/A

## Published
2013

## Last Updated
2014

## License
GPL-3

## Paper
http://www.ncbi.nlm.nih.gov/pubmed/24174567

## PMID
24174567
