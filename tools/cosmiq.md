# cosmiq
Version: 1.8.0

## Website
http://bioconductor.org/packages/release/bioc/html/cosmiq.html

## Description
This bioconductor package provides preprocessing for LC-MS or GC-MS metabolomics or lipidomics data. It is designed to improve the detection of low abundance signals by generating a master map of all mz/RT space before the peak detection algorithm is applied. It is built using the xcmsSet object structure and so can be integrated with xcms (it is suggested to use retcor.orbiwarp for RT alignment). It uses a continuous wavelet transformation (CWT) peak detection algorithm adapted from Du et al 2006. It includes the "quality_combined" function which is designed for use when there is no RT information available, so is suitable for peak picking of direct infusion experiments.

## Functionality
- Preprocessing

## Instrument Data Type
- MS/GC-MS
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
R (≥ 3.0.2), Rcpp

## Input Formats - Open
mzData, mzML, mzXML, netCDF

## Input Formats - Proprietary
N/A

## Published
2014

## Last Updated
2016

## License
GPL-3

## Paper

## PMID
