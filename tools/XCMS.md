# XCMS
Version: 3.0.0

## Website
http://bioconductor.org/packages/release/bioc/html/xcms.html

## Description
XCMS is a bioconductor package that provides preprocessing for LC-MS (and GC-MS and DI-MS) data. The following pipeline is used for preprocessing: peak picking, peak grouping, retention time alignment, peak regrouping and filling in missing values. XCMS currently provides five peak detection algorithms: matchedFilter and centWave are established methods; Massifquant, MS1-methods and MSW-methods have been more recently released. These different methods are optimised for different experimental setups. CentWave uses continuous wavelet transformation to pick peaks in centroid format high resolution LC-MS data, matchFilter is peck detection of low resolution data, Massifquant uses a 2D kalman filter for high resolution LC-MS peak picking (isotope trace detection, using the TracMass algorithm), MS1-methods are used to ensure the detection of MS1 precursor peaks, when MS1 and MS2 data are gathered quasi simultaneously, MSW-methods are for peak detection of DI-MS data (it is a wrapper of peak picking algorithm from the “MassSpecWavelet” package). Three methods for peak grouping are provided: group.density (peaks are grouped across samples into overlapping m/z bins), group.mzClust (high resolution alignment) and group.nearest (a master peak list is created and corresponding peaks from all samples are assigned - inspired the mzMine grouping algorithm). For retention time correction the methods available are: loess and obiwarp (Ordered Bijective Interpolated Warping). There are two methods for filling in missing data: one for chromatographic spectra, one for DI-MS. This is done by integrating the values of a peak group. It is also possible to analysis LC-MS/MS data with XCMS.

## Functionality
- Preprocessing

## Instrument Data Type
- MS/LC-MS/LC-MS/MS
- MS/GC-MS

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
R, C++

## Dependencies
mzR, BiocGenerics, ProtGenerics, Biobase

## Input Formats - Open
mzData, mzML, mzXML, netCDF

## Input Formats - Proprietary
N/A

## Published
2005

## Last Updated
2018

## License
GPL (≥ 2) and file license

## Paper
http://www.ncbi.nlm.nih.gov/pubmed/16448051

## PMID
16448051
