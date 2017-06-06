# EasyLCMS
Version: 1.0

## Website
http://www.easylcms.es/

## Description
This software both performs metabolite annotation and peak alignment, in a targeted fashion for LC-MS data. Metabolites are annotated from the KEGG, HMDB and PubChem databases. For annotation, multiple searches are avoided by checking the interconnectivity between databases. If internal standards are used, these can be uploaded in the table format and the quantification ion list can be saved for future use. There are three steps to data processing in EasyLCMS: raw data filtering, chromatograph construction and deconvolution (the algorithms used are from the MZmine team). The Savitzky-Golay smoothing filter can be applied for raw data filtering. A centroid algorithm is used for peak detection, with all data points above a specified noise level being detected. Continuous chromatographs are then constructed. Chromatogaphs are then deconvoluted (divided into individual peaks) using an algorithm which detects local minima in the chromatograph as border points between peaks. Different types of calibration curves (linear, logarithmic, power, exponential, quadratic polynomial and cubic polynomial) can then be used for calibration between peak area and concentration (the calibration curve). For calibration to be performed standard samples at known concentrations must be used. Peak candidates are suggested using the RANSAC algorithm. Data can then be visualised and results exported in the .CSV format.

## Functionality
- Preprocessing
- Annotation

## Instrument Data Type
- LC-MS

## Approaches
- Targeted

## Computer Skills
Basic

## Software Type
Web App

## Interface
Web user interface

## Operating System (OS)
- Unix/Linux
- Mac OS
- Windows

## Language
Microsoft. NET, Microsoft Silverlight 4.0

## Dependencies
Silverlight (for Mac OS and Windows)

## Input Formats - Open
mzML, mzXML, netCDF

## Input Formats - Proprietary
N/A

## Published
2012

## Last Updated
2012

## License
Free for academic users. For non-academic users a license is required.

## Paper
http://www.ncbi.nlm.nih.gov/pubmed/22884039

## PMID
22884039
