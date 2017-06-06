# MetaboliteDetector
Version: 2.5

## Website
http://md.tu-bs.de/

## Description
This provides preprocessing and metabolite identification of both targeted and non-targeted GC-MS data. For TOF data, a calibration function is included, to calibrate from TOF to m/z. The baseline of each spectra is first corrected, followed by applying a five point Savitzky-Golay filter to smooth the data if noise is present. Single ion peaks in the chromatogram are then detected using the first derivative of the smoothed intensity values and deconvolution is performed using an improved version of the algorithms applied by Colby et al. and Stein. After this, the m/z of potential compounds are extracted. It is recommended that the RI for each compound is calculated for metabolite identification. The user can provide a library of RIs for metabolite identification. Quantification is then performed and chromatographs are aligned by RT. There is also the option to perform PCA.

## Functionality
- Preprocessing

## Instrument Data Type
- MS/GC-MS

## Approaches
- Targeted
- Untargeted

## Computer Skills
Medium

## Software Type
Package

## Interface
- Command Line Interface
- Graphical User Interface

## Operating System (OS)
- Unix/Linux
- Mac OS
- Windows

## Language
C++

## Dependencies
N/A

## Input Formats - Open
netCDF

## Input Formats - Proprietary
JEOL FastFlight2

## Published
2009

## Last Updated
2014

## License
GPL

## Paper
http://www.ncbi.nlm.nih.gov/pubmed/19358599

## PMID
19358599
