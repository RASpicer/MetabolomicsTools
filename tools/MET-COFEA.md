# MET-COFEA
Version: Gamma

## Website
http://bioinfo.noble.org/manuscript-support/met-cofea/

## Description
MET-COFEA Metabolite compound feature extraction and annotation (MET-COFEA) provides a data analysis pipeline for LC-MS data, consisting of three modules: compound feature extraction, compound feature annotation and compound alignment. Mass traces are first extracted from each scan. The optimal mass trace candidate is then searched for. If two mass traces centroid masses are smaller than a user-defined threshold, they are merged. A continuous wavelet transformation (CWT) algorithm is then used for peak detection. To filter out bad peaks there are a number of options: peak intensity below a user-defined threshold, peak signal-to-noise ratio, peak significance level, zig-zag index and triangle peak area similarity ratio (TPASR). Next features are annotated with adducts and isotopes. After annotations, peaks are then grouped by dot-product to the highest intensity peaks by retention times and peak similarity. Compounds that fall into the same group, due to coelution and similar peak shapes are then separated using accurate mass information. There is also a peak refinement algorithm to separate peaks that cannot be separated by accurate mass (e.g. adduct peak intensities were too weak to be detected). HMDB is used for reference compound libraries to identify these peaks. Compounds are then aligned using a novel compound alignment strategy based on intensity ranks rather than elution time.

## Functionality
- Preprocessing

## Instrument Data Type
- MS/LC-MS

## Approaches
-

## Computer Skills
Medium

## Software Type
Package

## Interface
Graphical user interface

## Operating System (OS)
Windows

## Language
C++, .NET

## Dependencies
N/A

## Input Formats - Open
netCDF

## Input Formats - Proprietary
N/A

## Published
2013

## Last Updated
2016

## License

## Paper
http://www.ncbi.nlm.nih.gov/pubmed/24856452

## PMID
24856452
