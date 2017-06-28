# TagFinder
``` diff
- Deprecated
```

## Website
http://www.mpimp-golm.mpg.de/10871/Supplementary_Materials

## Description
This provides tools for the preprocessing of GC-MS data. It is recommended that data that has already been smoothed and baseline corrected is used, as these features are not available in TagFinder. Firstly sample classes are annotated. Internal standards are then used for RI calculation, using linear interpolation between RT anchors. Mass fragments are then sorted by m/z and RI, aligning and binning them into mass tags. Mass tags are grouped into time groups by the overlap of RI windows. As time groups can contain mass tags of multiple co-eluting compounds, Pearson/ Spearman correlation is used to find correlated clusters of tags. Compounds are then identified using RI libraries of authenticated standards. TagFinder is not currently available to download, as the link to the download page is missing. CORRECTOR, a TagFinder based tool for mass-isotope correction of GC-MS flux experiments is, but not TagFinder itself.

## Functionality
- Preprocessing
- Annotation/MS

## Instrument Data Type
- MS/GC-MS

## Approaches
- Metabolomics/Untargeted

## Computer Skills
Medium

## Software Type
- Package

## Interface
- Graphical User Interface

## Operating System (OS)
Unix/Linux

## Language
Java

## Dependencies
≥ 1.5 Java runtime environment

## Input Formats - Open
netCDF, MetAlign output

## Input Formats - Proprietary
N/A

## Published
2008

## Last Updated
2012

## License


## Paper
http://www.ncbi.nlm.nih.gov/pubmed/22351182

## PMID
22351182
