# flagme
Version: 1.30.0

## Website
https://bioconductor.org/packages/release/bioc/html/flagme.html

## Description
This bioconductor package processes and visualises GC-MS samples. It does not include support for peak detection (this can be done using AMDIS or ChromaTOF). It uses a dynamic programming-based alignment strategy - a similarity matrix is calculated based on a scoring function, taking into account similarity in RT and of the apex spectra, meaning that there are two components to the similarity: spectra and RT. A gap parameter must be set, with a high gap penalty discouraging gaps of peaks between spectra and a low gap penalty having very little cost for gaps (it is recommended to use 0.4-0.6). Similarly "D" modulates the penalty for RT difference penalty.  Provides visualisation of total ion current (TIC) or extracted ion current (XIC) and 2D heat maps of intensity for individual samples.

## Functionality
- Preprocessing

## Instrument Data Type
- MS/GC-MS

## Approaches
-

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
gcspikelite, xcms, CAMERA

## Input Formats - Open
AMDIS.elu

## Input Formats - Proprietary
ChromaTOF

## Published
2014

## Last Updated
2016

## License
LGPL (>=2)

## Paper

## PMID
