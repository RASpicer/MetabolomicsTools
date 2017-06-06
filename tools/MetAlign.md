# MetAlign
Version: 3

## Website
http://www.wageningenur.nl/en/show/MetAlign-1.htm

## Description
MetAlign provides preprocessing functions including noise reduction, missing value imputation, baseline correction, peak-picking and retention time alignment. Initially all data is converted to the netCDF format; during this conversion binning is performed. There is the option to process either nominal or accurate mass spectral data (but accurate requires a second baseline correction). There are two modes of alignment: respectively rough and iterative. A user defined windows runs through the time dimension in rough mode, with peaks within a mass trace being grouped by amplitude. Iterative mode uses the same algorithm as rough, but after, peaks that are present in all data sets are selected as landmarks. The number of landmark peaks present above a certain amplitude in a mass trace is then calculated. The average time dimension difference for each dataset is then calculated and this is used as input for the next iteration. The iterative cycle ends when the moving time window is in the order of a mass peak width.

## Functionality
- Preprocessing

## Instrument Data Type
- MS/GC-MS
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
Windows 7 (32 and 64 bit)/XP/NT/2000

## Language
Visual C++

## Dependencies
N/A

## Input Formats - Open
mzData, mzXML, netCDF

## Input Formats - Proprietary
Agilent .d, Masslynx .raw, Xcalibur .raw

## Published
2003

## Last Updated
2012

## License

## Paper
http://www.ncbi.nlm.nih.gov/pubmed/22833710

## PMID
22833710
