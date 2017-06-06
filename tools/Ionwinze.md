# Ionwinze
Version: 3.9.3.2

## Website
https://sourceforge.net/projects/ionwinze/

## Description
This provides preprocessing, pairwise comparison between 2 experimental conditions and statistical analysis. Positive and negative modes are analysed separately. First peaks are extracted and the data are then linearly normalised to the range 2^16 -1. The spectra of different classes are divided into equally sized segments of 1 m/z and 12 seconds RT. From these the mean ion currents and sd are obtained. The Z-factor is then calculated for each segment (z = 1 - 3(sd1 - sd2)/|mean1 - mean2|). The Z-factor is designed to be able to distinguish between conditions without the need of further statistical analysis. Univariate statistical analysis to determine significant differences between classes is also provided: coefficient of variation (CV), Student's t-test and z-test.

## Functionality
- Statistical Analysis

## Instrument Data Type
- MS/LC-MS

## Approaches
- Untargeted

## Computer Skills
Medium

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
ASCII, netCDF

## Input Formats - Proprietary
N/A

## Published
2013

## Last Updated
2016

## License
GPL-3

## Paper
http://www.ncbi.nlm.nih.gov/pubmed/24004415

## PMID
24004415
