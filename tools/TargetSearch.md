# TargetSearch
Version: 1.2.0

## Website
http://bioconductor.org/packages/2.5/bioc/html/TargetSearch.html

## Description
This Bioconductor packages provides both preprocessing and metabolite identification of GC-MS data: providing peak picking, RT alignment and metabolite identification via libraries. Features are picked using peak apex intensities rather than deconvolution as deconvolution can induce errors resulting in mixed mass spectral tags (MSTs). As input it requires raw data in the netCDF format (ideally pre-baseline corrected), a text file of metadata and a reference library of MSTs. For RT correction to be performed a tab separated file of retention time index (RI) markers must be provided. If baseline correction was not performed using the vendor software, this functionality is provided in TargetSearch. After this, peak apex intensities are used for peak picking. Retention time alignment is then performed using the RI. Metabolites can then be identified by user inputed libraries.

## Functionality
- Preprocessing

## Instrument Data Type
- MS/GC-MS

## Approaches
- Targeted

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
R, C

## Dependencies
R (≥ 2.7.0), mzR

## Input Formats - Open
netCDF

## Input Formats - Proprietary
N/A

## Published
2009

## Last Updated
2016

## License
GPL (≥ 2)

## Paper
http://www.ncbi.nlm.nih.gov/pubmed/20015393

## PMID
20015393
