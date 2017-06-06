# Metab
Version: 1.8.0

## Website
https://www.bioconductor.org/packages/release/bioc/html/Metab.html

## Description
This bioconductor package is designed for the analysis of GC-MS data preprocessed with AMDIS (Automated Spectral Deconvolution and Identification System). AMDIS deconvolutes spectra and provides metabolite identification via spectral libraries, however it has a number of limitations for use in metabolomics, as it outputs results as a spreadsheet per sample (or a merged sheet which requires a lot of manual processing before statistical analysis). It also has limited use in metabolite quantification (as it uses the area under the peak to do this, which may be influenced by the coelution of different metabolites) and may report more than one metabolite identified for the same mz/RT. Metab works to solve these limitations by selecting the most probable metabolite, correcting abundance calculation and presenting results in a single spreadsheet. It takes the AMDIS report and raw data in the netCDF format as input, requiring both for the function MetReport. It also has functions to remove false positives, normalise data by an internal standard, normalise by biomass and perform ANOVA or t-Test.

## Functionality
- Preprocessing

## Instrument Data Type
- MS/GC-MS
- MS/LC-MS

## Approaches
-

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
R (≥ 3.0.1) xcms, svDialogs

## Input Formats - Open
AMDIS.elu, netCDF

## Input Formats - Proprietary
N/A

## Published
2011

## Last Updated
2016

## License
GPL (≥ 2)

## Paper
http://www.ncbi.nlm.nih.gov/pubmed/21697128

## PMID
21697128
