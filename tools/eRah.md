# eRah
Version: 1.0.5

## Website
https://cran.r-project.org/web/packages/erah/index.html

## Description
eRah is a CRAN based package, which provides five processing steps: data preprocessing, spectral deconvolution, spectral alignment, missing compound recovery and compound identification. During preprocessing, baseline drift is removed using a moving-minimum filter and a Savitzky Golay filter is used to eliminate noise. Compound match by local covariance (CMLC), a multivariate matched filter and orthogonal signal deconvolution (OSD) are then used to extract compound spectra. The quantitative compound profile is obtained using a least absolute deviation (LAD) regression. Compounds are clustered by retention time distance and spectral similarity for retention time alignment. This method does not require retention indices for alignment, although they can be used to increase compound identification confidence. It is possible that the algorithm will fail to group the same compound in all samples, so a missing compound recovery step is used. For identification, eRah integrates ~500 compounds from MassBank or users can import their own libraries (not NIST).

## Functionality
- Preprocessing
- Annotation/MS

## Instrument Data Type
- MS/GC-MS/GC-TOF/MS
- MS/GC-MS/GC-qTOF/MS

## Approaches
-

## Computer Skills
Advanced

## Software Type
Package

## Interface
Command line interface

## Operating System (OS)
- Unix/Linux
- Mac OS
- Windows

## Language
R

## Dependencies
R (≥ 2.10), Rcpp

## Input Formats - Open
mzXML, netCDF

## Input Formats - Proprietary
N/A

## Published
2016

## Last Updated
2017

## License
GPL-2 | GPL-3

## Paper
http://www.ncbi.nlm.nih.gov/pubmed/27584001

## PMID
27584001
