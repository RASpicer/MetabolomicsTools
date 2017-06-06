# Astream
Version: 2.0

## Website
http://www.urr.cat/AStream/AStream.html

## Description
An R package for the annotation of preprocessed LC-MS data (a data.frame of features), detecting isotopes, adducts and fragments. xcmsSet objects can be directly imported into AStream. A quality control step is implemented to identify outlier peaks, which are then discarded. In this peaks below a given intensity are regarded as having 0 intensity and the counts for all samples are transformed into Z-scores, which are used to detect outliers with a high number of 0 intensities. Sample intensity quartiles for probabilities 0.1, 0.2, 0.3, 0.4 and 0.5 are also calculated and standardised as Z-scores. Samples with overly distinct intensity distribution profiles are then also discarded as outliers. The threshold levels for outlier detection can be modified by the user. Signal intensity is then normalised across samples. A pairwise correlation analysis across all features is then performed to identify features which are the same metabolic compound (due to fragmentation). HMDB metabolites are used for compound identification, using monoisotopic mass and biofluid/tissue location. Feature pairs corresponding to carbon isotopes of the same compounds are then identified. Adducts are then identified by searching for peaks within the m/z range of the expected m/z of the adduct.

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
R (≥ 3.0.1), multtest, Biobase, plotrix

## Input Formats - Open
data.frame, xcmsSet

## Input Formats - Proprietary
N/A

## Published
2010

## Last Updated
2014

## License
GPL (≥ 2)

## Paper
https://www.ncbi.nlm.nih.gov/pubmed/21414990

## PMID
21414990
