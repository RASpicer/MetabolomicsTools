# MetaboQC
Version: 1.0

## Website
http://evolution.haifa.ac.il/index.php/component/k2/item/146

## Description
MetaboQC provides a post-peaking QC procedure. The user must first run the peak picking software of their choice, under random parameters for 50-200 iterations. Each peak picking output (PP-output) then must be normalised inside each replicate group. The inter replicate correlation (AvCorr) and z-correlation (Zcorr) is then estimated across replicate groups. The PP-output with the best Zcorr and high enough AvCorr is then selected. There is also discrimination between replicate groups with high Zcorr and AvCorr and those with low to find parameters that provide high Zcorr and Avcorr. The peak picking software should then be run with these parameters. MetaboQC can then be used to detect local discrepancies between pairs of replicates and removing sample outliers. The output of MetaboQC then provides the parameter conditions with the least defects. The user can then manually remove features that are enriched in low score replicates

## Functionality
- Other Tools/Software Optimisation

## Instrument Data Type
- MS/LC-MS

## Approaches
- Untargeted

## Computer Skills
Advanced

## Software Type
Package

## Interface
Command line interface

## Operating System (OS)
Windows (32 bit)

## Language
C++

## Dependencies
N/A

## Input Formats - Open
mzData, mzML, mzXML, netCDF

## Input Formats - Proprietary
N/A

## Published
2010

## Last Updated
2013

## License

## Paper
http://www.ncbi.nlm.nih.gov/pubmed/20977194

## PMID
20977194
