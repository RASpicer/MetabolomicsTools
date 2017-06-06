# iMet-Q
Version: 1.001

## Website
http://ms.iis.sinica.edu.tw/comics/Software_iMet-Q.html

## Description
Intelligent Metabolomic Quantitation (iMet-Q) is designed to provide accurate quantification of LC-MS data. Firstly peaks are detected. Optionally centroiding can be performed. Noise is removed by dividing scans into segments with 20% overlap (avoiding borderline issues), defining the noise level for each segment and removing signals below a user-specified S/N. The FWHM of each peak is calculated to automatically determine the chromatographic width. The charge state of a peak is determined by calculating the similarity between the monoisotopic peak and the second most abundant isotopic peak. Isotopic ratios are then determined for metabolite identification using the dot product ratio. Peaks are first aligned across technical replicates, then across different biological samples, using LOESS regression.

## Functionality
- Preprocessing

## Instrument Data Type
- MS/LC-MS

## Approaches
-

## Computer Skills
Easy

## Software Type
Package

## Interface
Graphical User Interface

## Operating System (OS)
- Windows XP/7/8
- Windows Server 2008/2012

## Language
C#

## Dependencies
≥ .Net 4.0

## Input Formats - Open
mzML, mzXML, netCDF

## Input Formats - Proprietary
N/A

## Published
2015

## Last Updated
2015

## License
LGPL-2

## Paper
http://www.ncbi.nlm.nih.gov/pubmed/26784691

## PMID
26784691
