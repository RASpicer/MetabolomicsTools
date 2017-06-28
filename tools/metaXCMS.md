# metaXCMS
``` diff
- Deprecated
```
Version: 0.1.20

## Website
https://xcmsonline.scripps.edu/landing_page.php?pgcontent=mainPage

## Description
Designed for use in conjunction with XCMS and performs meta (second order) analysis for data reduction. Once data is loaded, the control group for each experiment is verified. After this features are filtered by either fold change, p-value or predefined list of up and down regulation. Features from separate experiments are then aligned by m/z and rt using the 'group.nearest' algorithm from XCMS. Any number of experiments can be compared using this method, but only 5 or less can be visualised using a VENN diagram, showing common features. Data then re-undergo retention time correction, using the OBI-Warp method, to verify results. metaXCMS is currently only available online as part of the XCMS Online software.

## Functionality
- Statistical Analysis

## Instrument Data Type
- MS/LC-MS

## Approaches
- Untargeted

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
GTK+, cairoDevice, RGtk2, gstat, RANN, xlsx, xcms, Biobase

## Input Formats - Open
XCMS output

## Input Formats - Proprietary
N/A

## Published
2010

## Last Updated
2012

## License

## Paper
http://www.ncbi.nlm.nih.gov/pubmed/22343432

## PMID
22343432a
