# RAMClustR
Version: 0.4

## Website
https://github.com/cbroeckl/RAMClustR

## Description
This is designed for the analysis of indiscriminate (data-independent-acquisition) MS/MS data that provides a feature grouping method. It takes a dataset preprocessed with XCMS as input (it can take data preprocessed by other software as input, but the user then needs to manually input parameters that are calculated automatically from the xcmsSet). Firstly quantile normalisation is available. If MS/MS data is present, to separate the MS and MS/MS the user can either tag the filename or file path. A custom similarity matrix using two Gaussian terms (one of the different between rt of two features and the other the correlation between two features across all samples) is used to group features. Pearson's correlation is used to calculate similarity. Features that are similar in both Gaussian terms are clustered using a similarity matrix.

## Functionality
- Preprocessing

## Instrument Data Type
- MS/LC-MS/LC-MS/MS

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
devtools

## Input Formats - Open
mzData, mzML, mzXML, netCDF

## Input Formats - Proprietary
N/A

## Published
2013

## Last Updated
2018

## License
GPL-2

## Paper
http://www.ncbi.nlm.nih.gov/pubmed/24927477

## PMID
24927477
