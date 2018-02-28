# IPO
Version: 1.4.1

## Website
https://github.com/glibiseller/IPO

## Description
Isotopologue parameter optimisation (IPO) is designed to increase the reliability of peak picking (centWave and matchedFilter), retention time alignment (orbiwarp) and grouping (density) of XCMS, by optimising the parameters. A design of experiments approach (DoE) is used to optimised parameters. Box-Behnken designs (BBD) are used to create DoE. Feature detection parameters are optimised first, followed by simultaneous optimisation of retention time correction and group parameters. Peak picking scores are calculated based on the ratio of reliable peaks (isotopologues). Relative retention time deviations are minimised to produce the retention time correction score (RCS) using the inverse of the average retention time score. The ratio of the squared reliable groups to non-reliable groups is the grouping scores (GS). The norms of the RSC and GS are then combined as the retention time correction and grouping target value (RGTV). These scores are the evaluated using response-surface models. The centre of the next DoE is the combination of parameters that produced the best score in the response-surface models.

## Functionality
- Other Tools/Software Optimisation

## Instrument Data Type
- MS/LC-MS

## Approaches
- Untargeted

## Computer Skills
Medium

## Software Type
R Package

## Interface
Command line interface

## Operating System (OS)
Unix/Linux, Mac OS, Windows

## Language
R

## Dependencies
xcms, rsm, CAMERA, grDevices, graphics, stats, utils

## Input Formats - Open
mzData, mzML, mzXML, netCDF

## Input Formats - Proprietary
N/A

## Published
2015

## Last Updated
2017

## License
GPL (≥ 2) + file LICENSE

## Paper
http://www.ncbi.nlm.nih.gov/pubmed/25888443

## PMID
25888443
