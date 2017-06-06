# mQTL.NMR
Version: 1.8.0

## Website
https://www.bioconductor.org/packages/release/bioc/html/mQTL.NMR.html

## Description
mQTL.NMR, a bioconductor package, provides a complete mQTL analysis pipeline for 1H NMR data, including processing, statistical analysis between metabolites and QTL and visualisation. NMR data should be preprocessed before being loaded into mQTL.NMR (FT, apodization, calibration, phasing and baseline correction). A number of normalisation approaches are provided: constant sum, constant noise, linear baseline and probabilistic quotient normalisation. Two scaling options are available: Pareto and autoscaling. Recursive segment wise peak alignment (RSPA) is used for peak alignment. There are two approaches to reduce dimensionality for mapping metabolites to QTLs: bucketing and statistical recoupling of variables (SRV). For animal crosses, the extended Haley-Knott regression method is used. For human mapping, simple linear regression is used to map SNPs to metabolites. Other covariants such as sex and age can also be taken into account in the model, due to the use of GenABEL.

## Functionality
- Statistical Analysis

## Instrument Data Type
- NMR/1H NMR

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
R ≥ 2.15.0, qtl, GenABEL

## Input Formats - Open
Text file

## Input Formats - Proprietary
N/A

## Published
2015

## Last Updated
2016

## License
Artistic-2.0

## Paper
http://www.ncbi.nlm.nih.gov/pubmed/25803548

## PMID
25803548
