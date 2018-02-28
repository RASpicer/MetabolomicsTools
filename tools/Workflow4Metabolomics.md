# Workflow4Metabolomics
Version: 3.0

## Website
http://workflow4metabolomics.org/

## Description
Workflow4Metabolomics provides a comprehensive tool for metabolomics data preprocessing, statistical analysis and annotation. It is built in the galaxy environment and accessible as a web-based tool. It encompasses analysis pipelines for LC-MS, GC-MS and NMR, with LC-MS being the most comprehensive and NMR being the least. In the LC-MS workflow, data are preprocessing using XCMS (xcmsSet, group, retcor, group, fillPeaks) and annotated using CAMERA. Alternatively it is possible to upload a peak list of already preprocessed data for further analysis. Features can then be filtered and batch correction (linear or loess) can be performed. A number of univariate: Student's t test, Wilcoxon t test, ANOVA, Kruskal-Wallis test, Pearson or Spearman correlation test and multivariate: PCA, PLS, OPLS and PLS-DA (integrated as part of the ropls package). For Putative Metabolite Annotation HMDB, LipidMaps, KEGG-compounds and ChemSpider can be searched. Also MassBank can be searched. The HiRes algorithm can be used for empirical formula identification. GC-MS data is also preprocessed using XCMS and the same statistical analysis can be used. Metabolites can be identified using Golm or NIST if the user has it installed. For NMR a full pipeline is not available. Instead three functions are provided: Bruker bucketing and integration, normalisation (total intensity, quantitative variable and probabilistic quotient) and statistical analysis.

## Functionality
- Workflow

## Instrument Data Type
- MS/LC-MS

## Approaches
-

## Computer Skills
Medium

## Software Type
Package

## Interface
Graphical User Interface

## Operating System (OS)
- Unix/Linux
- Mac OS
- Windows

## Language
Galaxy

## Dependencies
N/A

## Input Formats - Open
mzData, mzML, mzXML, netCDF

## Input Formats - Proprietary
N/A

## Published
2014

## Last Updated
2017

## License
GPL-3

## Paper
http://www.ncbi.nlm.nih.gov/pubmed/25527831

## PMID
25527831
