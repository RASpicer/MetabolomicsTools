# GAVIN
``` diff
- Deprecated
```
Version: 1.07

## Description
GC-MS Assignment Validator and Integrator (GAVIN) is designed to compliment AMDIS (it cannot be used alone), which used alone has a high false positive rate and generates many missing values. GAVIN produces a cleaned peak table with the results from different samples integrated. The multiple AMDIS output files (.elu and .fin) are combined to produce a peak table of metabolites identified in at least one spectrum. A use defined threshold of samples a feature must be present in to be considered a metabolite is used. A quantification ion (QI) and 2 validation ions (VI) are extracted from the compound with the lowest mean retention time. The QI can be integrated over the integration region, which can also have its parameters altered. There is the option to remove a peak from all samples. The software is available in the supplementary material.

## Functionality
-

## Instrument Data Type
- MS/GC-MS

## Approaches
- Metabolomics/Targeted

## Computer Skills
Advanced

## Software Type
- MATLAB Script

## Interface
- Command line interface

## Operating System (OS)
- Unix/Linux
- Mac OS
- Windows

## Language
MATLAB, Perl

## Dependencies
N/A

## Input Formats - Open
AMDIS.elu, netCDF

## Input Formats - Proprietary
N/A

## Published
2011

## Last Updated
2011

## License

## Paper
http://www.ncbi.nlm.nih.gov/pubmed/21575589

## PMID
21575589
