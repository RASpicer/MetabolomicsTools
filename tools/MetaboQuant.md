# MetaboQuant
Version: 1.3

## Website
http://genomics.uni-regensburg.de/site/institute/software/metaboquant

## Description
This program calculates accurate compound concentrations of 1D and 2D NMR spectra. Peak integrals are divided by the number of nuclei contributing to each peak. Before this step, the peak integrals may first be scaled to a reference substance and given as a fraction of the integral (FI). Each FI may then be individually calibrated. Some calibration factors are included in MetaboQuant, however these are only appropriate for experiments conducted under the same conditions. The user may instead include their own calibration factors or if no calibration factors are available, each FI can be multiplied  by the reference compound concentration. As some compounds are prone to multiple, overlapping peaks, the user can specify which peaks to use for quantification. For the quantification of low abundance peaks the user may define a threshold of expected to observed peaks, below which the compound is not quantified. As a reliability check to ensure that compounds which are present in the sample are not excluded, the maximum number of nuclei observed (MMO) and the maximum number of unobserved (MNN) are collected. If MMO > MNN then the compound is further considered, otherwise it's concentration is set to 0. Peaks are counted as outliers and excluded from analysis if their integrals deviate by more than a given threshold. After outlier removal, the mean of the remaining peaks is calculated to acquire the metabolite concentration.

## Functionality
-

## Instrument Data Type
- NMR/1D NMR
- NMR/2D NMR

## Approaches
-

## Computer Skills
Advanced

## Software Type
- Package

## Interface
- Command line interface

## Operating System (OS)
- Unix/Linux
- Mac OS
- Windows

## Language
MATLAB

## Dependencies
≥ MATLAB 7.1.0.246

## Input Formats - Open
Tab separated text file, excel file

## Input Formats - Proprietary
Amix

## Published
2013

## Last Updated
2013

## License

## Paper
http://www.ncbi.nlm.nih.gov/pubmed/23662895

## PMID
23662895
