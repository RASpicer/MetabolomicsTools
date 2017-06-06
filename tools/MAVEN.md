# MAVEN
Version: 769

## Website
http://genomics-pubs.princeton.edu/mzroll/index.php

## Description
Metabolomics and visualisation engine (MAVEN) provides a processing pipeline for LC-MS data including: preprocessing, annotation and metabolite identification. For feature detection each scan is sequentially searched for consecutive scans containing the same m/z within the user set mass error, if an m/z value fulfills this requirement, then it is considered a feature. A binary search algorithm is used to extract the EIC from every retention time window. The EIC baseline is then calculated by first removing the 20% most intense peaks then Gaussian smoothing is used on the remaining peaks. Peaks are then grouped across samples: EICs for a given m/z are summed across samples and these define 'groups', which individual EICs are assigned by overlapping retention times. Retention times are then aligned using iterative fitting with a global third degree polynomial. Peak quality scores are reported to enable to user to identify high quality peaks. KEGG Compounds can be used to putatively identify features. Significant difference between the metabolites of two datasets can be identified by using fold-change calculations.

## Functionality
- Workflow

## Instrument Data Type
- MS/LC-MS

## Approaches
- Untargeted

## Computer Skills
Advanced

## Software Type
Package

## Interface
Graphical user interface

## Operating System (OS)
- Unix/Linux
- Mac OS
- Windows

## Language
C++

## Dependencies
N/A

## Input Formats - Open
mzXML

## Input Formats - Proprietary
N/A

## Published
2008

## Last Updated
2013

## License

## Paper
http://www.ncbi.nlm.nih.gov/pubmed/21049934

## PMID
21049934
