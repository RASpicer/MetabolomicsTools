# Credential Features
Version: 1.0

## Website
http://pattilab.wustl.edu/software/credential/credential.php

## Description
This package is designed to optimise LC-MS workflows where 1000s of features are detected from a single run. It uses credentialling to identify features which are artificial as opposed to those of biological origin. To do this E.coli were grown on either natural abundance media or uniformly C13 (UC13) media. These two media were then mixed at different ratios (1:1 and 1:2). Once LC-MS analysis has then be performed. The credential features package is used for data analysis. XCMS and CAMERA are utilized for preprocessing and annotation respectively. The credential features algorithm performs two rounds of filtering to identify biological features. Firstly, coeluting peaks within a single sample are assessed for potential isotopologue pairs and the ratios of 12C:13C are then evaluated and those that are not within a set percentage are discarded. The samples with different ratios of C12:C13 are then taken together for a second round of filtering.

## Functionality
- Other Tools/Experimental Optimisation

## Instrument Data Type
- MS/LC-MS

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
xcms, data.table, plyr, CAMERA, ggplot2, gridExtra, Hmisc

## Input Formats - Open

## Input Formats - Proprietary

## Published
2014

## Last Updated
2015

## License

## Paper
http://www.ncbi.nlm.nih.gov/pubmed/25160088

## PMID
25160088
