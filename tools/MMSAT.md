# MMSAT
Version: 1.1

## Website
http://powcs.med.unsw.edu.au/research/adult-cancer-program/services-resources/mmsat

## Description
Metabolite Mass Spectrometry Analysis Tool (MMSAT) is designed for the automated quantification of selected reaction monitoring (SRM) data, which is acquired from QQQ mass spectrometers. First the transitions present, based on the scans, are determined. XIC are then constructed for each transition. For each XIC, peak detection is then performed, using smoothing and optionally denoising using Savitzky-Golay smoothing and wavelet shrinkage denoising. All maxima above a user-defined intensity threshold are then found. The base of each peak is then found and the AUC is calculated. Peaks are then aligned across samples using an iterative pairwise comparison. Whether 2 peaks come from the same metabolite is determined by whether they come from the same transition and their retention time difference must be below a user-defined threshold.

## Functionality
- Preprocessing
- Annotation/MS

## Instrument Data Type
- MS/GC-MS/GC-MS SRM
- MS/LC-MS/LC-MS SRM

## Approaches
- Targeted

## Computer Skills
Basic

## Software Type
Web App

## Interface
Web user interface

## Operating System (OS)
- Unix/Linux
- Mac OS
- Windows

## Language
C++, python

## Dependencies
N/A

## Input Formats - Open
.mzXML

## Input Formats - Proprietary
N/A

## Published
2011

## Last Updated
2011

## License
Non-commerical

## Paper
http://www.ncbi.nlm.nih.gov/pubmed/22111688

## PMID
22111688
