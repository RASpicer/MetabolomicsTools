# MetExtract
Version: 1

## Website
https://code.google.com/archive/p/metextract/

## Description
This is designed for the analysis of isotopically labelled mass spectrometry data. It aims to elucidate signals of natural and stable isotopically labelled metabolites and combine these, to allow assignment of the biological metabolites. For this the experimental design must include two samples, that only differ in isotopic labelling of one specific element, with one being labelled and the other not. Initially all peaks above a certain threshold are considered to be the monoisotopic peak of a non-labelled metabolite. A defined range of atom numbers is then used to find the corresponding labelled isotopologue. Pearson's Correlation Coefficient is then calculated for the EIC of both labelled and unlabelled molecules. Only if the isotopic peaks for both are found is the peak added to the m/z list. The picked m/z values are then binned according to m/z and rt similarity using hierarchical clustering. This does not separate structural isomers. The binned data are then searched for adducts and fragments using an m/z value offset list.

## Functionality
- Preprocessing

## Instrument Data Type
- MS/LC-MS/Centroid LC-MS

## Approaches
- Untargeted
- Isotopic Labelling Analysis

## Computer Skills
Advanced

## Software Type
Package

## Interface
Command line interface

## Operating System (OS)
Windows (Full binaries only available for Windows XP)

## Language
C++

## Dependencies
N/A

## Input Formats - Open
mzXML

## Input Formats - Proprietary
N/A

## Published
2011

## Last Updated
2012

## License
MIT License

## Paper
http://www.ncbi.nlm.nih.gov/pubmed/22238263

## PMID
22238263
