# X13CMS
Version: 1.4

## Website
http://pattilab.wustl.edu/software/x13cms/x13cms.php

## Description
This is an extension of XCMS that provides support for isotopic labelling. It requires two biologically identical samples to be prepared, with isotopic labelling being applied to one of them. XCMS is used for peak detection and retention time alignment, with the table of putative detected peaks being forwarded to X13CMS. X13CMS function getIsoLabelReport() can then be used to detect which metabolites have been enriched with isotopic labelling. This function detects the difference in mass between labelled and unlabelled samples and outputs a table of isotopologues that have statistically significant isotopic labelling. It requires that the mean intensity of the labelled peak be less than the unlabelled peak. getIsoDiffReport() then compares labelling between different biological conditions, to find significant biological differences between them (using a Welch's t-test).

## Functionality
- Preprocessing

## Instrument Data Type
- MS/LC-MS

## Approaches
- Untargeted
- Isotopic Labelling Analysis

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
xcms, mzR, Rcpp, BioGenerics, Biobase

## Input Formats - Open
mzData, mzML, mzXML, netCDF

## Input Formats - Proprietary
N/A

## Published
2014

## Last Updated
2014

## License

## Paper
http://www.ncbi.nlm.nih.gov/pubmed/24397582

## PMID
24397582
