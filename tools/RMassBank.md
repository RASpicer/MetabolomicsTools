# RMassBank
Version: 2.6.0

## Website
https://bioconductor.org/packages/release/bioc/html/RMassBank.html

## Description
This bioconductor package is designed to allow for easy upload of data onto MassBank. Initially MS/MS spectra are extracted from raw data files. Then using a .csv containing the compound information, RMassBank attempts to fit molecular formulas for every peak. This generates an array of metabolites, which is then aggregated into a list. A calibration curve is then calculated from this list and all spectra are then recalibrated. The recalibrated spectra are then reanalysed and aggregated and know electronic noise is removed. Peaks without a compound identification are then reanalysed, allowing for N2O as an additional element. After this peaks that are only found in a single spectra are removed. After this annotated spectra can be uploaded onto MassBank. Additionally XCMS can be used to extract the MS2 spectra (optionally the MS1) and then for peak picking. CAMERA can then be used to process the spectra.

## Functionality
- Other Tools

## Instrument Data Type
-

## Approaches
- Targeted

## Computer Skills
Advanced

## Software Type
R Package

## Interface
Command line Interface

## Operating System (OS)
- Unix/Linux
- Mac OS
- Windows

## Language
R

## Dependencies
Rcpp

## Input Formats - Open
mzML, mzData

## Input Formats - Proprietary
N/A

## Published
2013

## Last Updated
2018

## License
Artistic-2.0

## Paper
http://www.ncbi.nlm.nih.gov/pubmed/23303751

## PMID
23303751
