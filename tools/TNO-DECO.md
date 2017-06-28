# TNO-DECO
Version: 1

## Website
https://github.com/NetherlandsMetabolomicsCentre/TNO-DECO

## Description
This builds on the multiple curve resolution - alternating least squares (MCR-ALS) deconvolution technique, splitting the data into segments, that are subsequently deconvoluted. This results in the deconvolution of all spectra simultaneously. It is specifically designed for the analysis of GC-MS data, but can also be applied to LC-MS data (the pipeline follows a standard GC-MS analysis where baseline correction is performed first). Initially spectra are baseline corrected, with four options being available: Groningen (for LC-MS), TNO, convex hull (still experimental) and Eilers methods. Following this, they are aligned. For this a reference spectra is used to compare each file to. At this stage there is the option to filter peaks by their intensities, peak width and rt. The spectra are then combined in a single file and traces that do not occur in all spectra are eliminated. An svd-based rank estimation is then used to compare the eigenvalues of the mean centre spectra and a random data block. The point where the mean centre spectra drop below the random data is marked as the number of compounds in the block. The data is the deconvoluted block wise using multiple curve resolution, alternating least squares under a non-negative and unimodal resolution. Data can then be directly exported into NIST.

## Functionality
- Preprocessing

## Instrument Data Type
- MS/LC-MS
- MS/GC-MS

## Approaches
- Metabolomics/Untargeted

## Computer Skills
Advanced

## Software Type
- MATLAB Script

## Interface
- Graphical User interface

## Operating System (OS)
- Unix/Linux
- Mac OS
- Windows

## Language
MATLAB

## Dependencies
N/A

## Input Formats - Open
netCDF

## Input Formats - Proprietary
N/A

## Published
2010

## Last Updated
2014

## License
GPL-2

## Paper
http://www.sciencedirect.com/science/article/pii/S0169743910001383
