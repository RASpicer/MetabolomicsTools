# MetMSLine
Version: 1.2.1

## Website
http://wmbedmands.github.io/MetMSLine/

## Description
This package provides a workflow for untargeted LC-MS data, including normalisation, smoothing, biomarker selection, annotation and metabolite identification. As input this package requires a peak list. Zero-filling is first performed, then median fold-change normalisation can be applied if required. QC-based locally weighted scatterplot smoothing is then used to alleviate the effect of signal drift. Data are then log transformed and features which are found stability across pooled samples are maintained. Outliers are then removed using expansion of Hotelling's T2 distribution ellipse (samples beyond this ellipse but within first/second compound PCA plot are removed). Potential biomarkers are then identified using multivariate regression and visualised with heatmaps. Using MS/MS data, features can then be identified by matching to fragments MS/MS spectra. Metabolites can also be identified via a user-inputed .csv database of compounds and their exact masses.

## Functionality
- Workflow

## Instrument Data Type
- MS/LC-MS

## Approaches
- Untargeted

## Computer Skills
Advanced

## Software Type
R Package

## Interface
- Command line interface
- Graphical user interface

## Operating System (OS)
- Unix/Linux
- Mac OS
- Windows

## Language
R

## Dependencies
R (≥ 3.2.0), fgui, tcltk2, zoo, gplots, ggplot2, sfsmisc, RColorBrewer, readMzXmlData

## Input Formats - Open
Peaklist (xcms), covariate table (.csv)

## Input Formats - Proprietary
N/A

## Published
2014

## Last Updated
2017

## License
GPL-3

## Paper
http://www.ncbi.nlm.nih.gov/pubmed/25348215

## PMID
25348215
