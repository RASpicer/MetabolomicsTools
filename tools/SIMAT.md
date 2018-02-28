# SIMAT
Version: 1

## Website
http://bioconductor.org/packages/3.1/bioc/html/SIMAT.html

## Description
This bioconductor package performs preprocessing and metabolite identification of selective ion monitoring (SIM) GC-MS data. Firstly, then most unique fragment (optimal fragment) must be manually selected. Next, baseline correction is performed on the individual fragments. Next a smoothing filter is used. Peaks are then detected by finding all candidate peaks in the vicinity of the expected RT and evaluating them. Each EIC is then evaluated for its quality, to decide whether or not it is included when estimating the similarity score or the peak intensity. RI calibration is then performed, using a piecewise linear regression model of RT - it is recommended to use RI standards for this. For feature identification a mixed score of the weighted dot-product of the spectra and average pairwise intensity comparisons between 2 spectra using the ratios of all fragments. The user can choose AUC-based or apex-based scores. The intensity of each fragment is then calculated using both the AUC and the apex. Both the TIC and EICs can be visualised using SIMAT. This is also available as a MATLAB script.

## Functionality
- Preprocessing

## Instrument Data Type
- MS/GC-MS/GC-MS - SIM

## Approaches
- Targeted

## Computer Skills
Advanced

## Software Type
- R Package
- MATLAB Script

## Interface
Command line interface

## Operating System (OS)
- Unix/Linux
- Mac OS
- Windows

## Language
R/ MATLAB

## Dependencies
R (≥ 3.0.0), Rcpp (≥ 0.11.3)

## Input Formats - Open
netCDF, target peak list

## Input Formats - Proprietary
N/A

## Published
2015

## Last Updated
2016

## License
GPL-2

## Paper
http://www.ncbi.nlm.nih.gov/pubmed/26283310

## PMID
26283310
