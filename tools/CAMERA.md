# CAMERA
Version: 1.30.0

## Website
http://bioconductor.org/packages/release/bioc/html/CAMERA.html

## Description
CAMERA (Collection of Algorithms for MEtabolite pRofile Annotation) is designed as an add-on to XCMS, providing additional grouping based on retention time and chromatographic peak shape and isotopic peaks and adduct annotation. Features are first grouped by their retention times, using 60% of the FWHM around the centroid of the most intense feature that is not yet assigned a compound spectrum. Isotopic peaks are then detected by calculating a pairwise distance matrix and detecting isotopes exhibiting a 1.0033 m/z difference. Chromatographic peak shape is then used to improve spectral separation (pointwise pearson correlation of the intensities between the chromatographic peak boundaries between all pairs of features of a single EIC, pointwise pearson correlation of the intensities between the chromatographic peak boundaries between all pairs of features of all samples and isotope relationship between two features, which are then plotted as scores on a relationship graph using either the Highly-connected-subgraphs or label propagation community algorithms). Adducts, common neutral losses and cluster ions are then annotated using a dynamic rule set, which is then matched against m/z differences. Annotations made in positive and negative mode are then combined and compounds that are detected in both are verified using a novel algorithm and a cross-polarity rule table.

## Functionality
- Annotation/MS/Level 4 - Unequivocal Molecular Formula

## Instrument Data Type
- MS/LC-MS

## Approaches
- Metabolomics/Untargeted

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
R (≥ 2.1.0), methods, Biobase, xcms (>= 1.13.5), igraph

## Input Formats - Open
mzData, mzML, mzXML, netCDF

## Input Formats - Proprietary

## Published
2009

## Last Updated
2016

## License
GPL (≥ 2)

## Paper
http://www.ncbi.nlm.nih.gov/pubmed/22111785

## PMID
22111785
