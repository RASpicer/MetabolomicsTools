# metabomxtr
Version: 1.8.0

## Website
https://www.bioconductor.org/packages/release/bioc/html/metabomxtr.html

## Description
This bioconductor packages uses the Bernoulli/lognormal mixture-model (Moulton and Halsey, 1995) to formally account for individual metabolite 'missingness". It simultaneously estimates parameters, modeling the probability of a non-missing response and the mean of observed values. To do this it requires the input of the parameter of interest (i.e. the phenotypic difference) and the number of samples per group. The model can be controlled for confounding factors. After the full model containing the parameter of interest has been run, a reduced model without the parameter of interest is run. The significance of the full and reduced models is then compared using nested likelihood chi-squared tests. A results table can then be generated. This package is designed to be run for individual metabolites with missing values, not across the whole dataset.

## Functionality
- Post-Processing

## Instrument Data Type
- MS/GC-MS
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
methods, Biobase

## Input Formats - Open
Matrix, Data frame

## Input Formats - Proprietary
N/A

## Published
2014

## Last Updated
2016

## License
GPL-2

## Paper
http://www.ncbi.nlm.nih.gov/pubmed/25075114

## PMID
25075114
