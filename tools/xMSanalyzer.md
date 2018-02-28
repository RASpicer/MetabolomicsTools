# xMSanalyzer
Version: 2.0.6.1

## Website
https://sourceforge.net/projects/xmsanalyzer/

## Description
Designed to improve feature detection of LC-MS data, running in conjunction with XCMS or apLCMS. As the scanning intervals with Fourier transform mass spectrometers is relatively constant, the optimum number of points to define a peak can vary over the course of a run. To deal with this, xMSanalyzer selects the number of points that is most reproducible for each peak, allowing for the extraction of low intensity peaks and those found in only a few samples. Sample quality is then evaluated using mean pairwise Pearson correlation coefficient between sample replicates. Quantitative feature reproducibility across sample replicates can then be evaluated using percent intensity difference (PID) or coefficient of variation (CoV). There is also the option of merging features detected using different parameter settings. Features can be matched across samples based on their m/z and their retention time. Features that are present in only single/few biological replicates but across multiple technical replicates can also be detected. It annotate metabolites using the METLIN and KEGG databases.

## Functionality
- Preprocessing

## Instrument Data Type
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
Rcpp, mzR, R2HTML, XML, limma, xcms, snow, rgl, gplots, foreach, RCurl, doSNOW, apLCMS

## Input Formats - Open
mzData, mzML, mzXML, netCDF

## Input Formats - Proprietary
N/A

## Published
2013

## Last Updated
2015

## License
GPL-2

## Paper
http://www.ncbi.nlm.nih.gov/pubmed/23323971

## PMID
23323971
