# MetaboLyzer
Version: 1.00

## Website
https://sites.google.com/a/georgetown.edu/fornace-lab-informatics/home/metabolyzer

## Description
This software aims to identify features which have significantly different signal intensities between two treatment conditions (only 2 conditions can be analysed). First features that are not present in user-defined percentage of samples of one of the conditions are filtered (removal of missing values). Data are then segmented into two categories: partial presence (data only above threshold for one condition) and complete presence (data above threshold in both conditions). Data can then be transformed (log or inverse hyperbolic sine) and data which are log transformed then have the option of being gaussian normalised. Data with partial presence are then analysed with Fisher's exact test and data with complete presence are analysed with a variety of statistical techniques: Student's t test, Welch's t test, Mann-Whitney U test, Kolmogorov-Smirnov test, Anderson-Darling test for normality, confidence intervals, fold-change, mean and standard deviation. A volcano plot is then produced and multivariate analysis can then be performed (PCA, multidimensional scaling (MDS), kernel PCA and independent component analysis (ICA)). Lastly a heatmap is constructed. Features are putatively identified using KEGG, BioCyc, LipidMaps and HMDB. A correlation analysis can be performed after the initial analysis is completed (correlation matrices of the two conditions are first created, followed by hierarchical clustering, then Fisher's transformations coupled to Z test are used to evaluate significance and a correlational heatmap is produced).

## Functionality
- Statistical Analysis

## Instrument Data Type
-

## Approaches
-

## Computer Skills
Advanced

## Software Type
Package

## Interface
Command line interface

## Operating System (OS)
- Unix/Linux
- Mac OS
- Windows

## Language
Python, R

## Dependencies
scipy, numpy, matplotlib, rpy2, lxml, gplots, kernlab, MASS, fastICA, ICSNP, mvnormtest

## Input Formats - Open
Peaklist

## Input Formats - Proprietary
N/A

## Published
2013

## Last Updated
2013

## License

## Paper
http://www.ncbi.nlm.nih.gov/pubmed/24266674

## PMID
24266674
