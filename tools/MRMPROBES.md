# MRMPROBES
Version: 2.42

## Website
http://prime.psc.riken.jp/Metabolomics_Software/MRMPROBS/index.html

## Description
Multiple reaction monitoring based probabilistic system for widely targeted metabolomics (MRMPROBES) is a RIKEN software that provides automatic detection and annotation of fragments from MRM experiments, as well as statistical analysis. Firstly peaks are detected and smoothed and peak groups are found. Peaks are detected by first finding the median amplitude (AF), first-order derivative (FF) and second-order derivative (SF) (the derivatives are calculated using Savitzky-Golay filter). The maximum amplitude difference between two adjacent peaks is detected, as well as the maxima between the first and second order derivatives. The edges of the peaks are recognised when the amplitude and first order derivative are both greater than AF and FF in two adjacent points and the tip is recognised when the sign of the first derivative changes and the second order derivative is less than SF. Metabolite peaks are then evaluated by posterior probability (the odds ratio in multivariate logistic regression) using: peak intensity, retention time, qualifier/target ratio, shape and coelution similarity, with each peak being assigned a score. The Gaussian function is used to assess retention time and QT ratio, peak intensity is assessed by comparing the height of the peak to the highest peak of all transition records and the rank of the peak intensity in a focused transition record and shape and coelution were assessed with the mProphet algorithm. The qualifier/target ratio is used for the assessment of peak groups, where the target is the transition which is used to quantify the metabolite and the qualifier transitions are the remaining transitions used for qualification (discrimination from background noise and isomeric metabolites). Peak groups with the highest probability are then selected as the quantification value. During this process, metabolites are identified by comparison to a reference library. The metabolite intensities can then be normalised to an internal standard using the LOESS of the second-degree least-squares with a robust tri-cubic weight function. Statistical analysis can then be performed with PCA and multi t-tests being provided.

## Functionality
- Preprocessing

## Instrument Data Type
- MS/GC-MS/GC-QqQ-MS
- MS/LC-MS/LC-QqQ-MS

## Approaches
-

## Computer Skills
Basic

## Software Type
Package

## Interface
Graphical user interface

## Operating System (OS)
Windows

## Language
C#

## Dependencies
≥ .NET Famework 4.0

## Input Formats - Open
Reifycs .ABF, .mzML

## Input Formats - Proprietary
Agilent .d, AB Sciex .wiff, Thermo Fisher Scientific .raw, Shimadzu .LCD

## Published
2013

## Last Updated
2018

## License

## Paper
http://www.ncbi.nlm.nih.gov/pubmed/23581547

## PMID
23581547
