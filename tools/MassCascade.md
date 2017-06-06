# MassCascade
Version: 1

## Website
https://bitbucket.org/beisken/masscascade

## Description
MassCascade is implemented in the KNIME workflow environment or alternatively can be accessed via the command line. It provides a modular pipeline for the analysis of LC-MS^n data. Data should be in the centroid format or they can be centroided with the implemented wavelet-based centroider. Firstly, a mass trace is built. The background is the subtracted and noise is reduced. At this stage the user can visualise the scans/ TIC. The data can then be normalised and filtered. Retention time alignment is performed using the obiwarp algorithm. For deconvolution Biemann and Savitzky Golay deconvolution are offered. Features can be compiled using Biemann or cosine compilers. A number of different filters are provided: Durbin, Feature and Mass. Two methods of smoothing are provided: Savitzky Golay smoother and Top Hat. For Putative Metabolite Annotation ChemSpider, MassBank and Metlin databases can be searched. Adducts can also be automatically annotated.

## Functionality
- Workflow

## Instrument Data Type
- MS/LC-MS/LC-MS/MS
- MS/LC-MS/LC-MS^n"

## Approaches
-

## Computer Skills
Medium

## Software Type
Package

## Interface
- Command line interface
- Graphical user interface

## Operating System (OS)
- Unix/Linux
- Mac OS (not Mac OS for KNIME)
- Windows

## Language
Java

## Dependencies
N/A

## Input Formats - Open
mzML

## Input Formats - Proprietary
Thermo Scientific .raw

## Published
2013

## Last Updated
2014

## License
GPL-3

## Paper
https://www.ncbi.nlm.nih.gov/pubmed/26279687

## PMID
26279687
