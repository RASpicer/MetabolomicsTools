# batchCorr
Version: 0.1.8

## Website
https://gitlab.com/CarlBrunius/batchCorr

## Description
This is designed for between and within-batch correction of LC-MS data. There are functions for batch alignment, drift correction and batch normalisation. For batch alignment feature missingness is aggregated on a batch level, features with missingness that are sufficiently similar m/z and retention time and ensuring orthogonal batch presence among feature alignment candidates. Drift correction is performed using clustering (mclust) on features in observation space. It provides a trade-off between the power per drift pattern and the multiple drift patterns within the dataset. For batch normalisation either QC/Reference or population (median) normalisation can be used. A quality heuristic is used to determine whether the QC/Reference is suitable for normalisation; if it is not, median normalisation is used instead.

## Functionality
- Post-processing

## Instrument Data Type
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
R (≥ 2.10)

## Input Formats - Open
Peaklist, xcmsSet

## Input Formats - Proprietary
N/A

## Published
2016

## Last Updated
2017

## License
GPL-2

## Paper
http://www.ncbi.nlm.nih.gov/pubmed/27746707

## PMID
27746707
