# mzMatch
Version: 2.0-13

## Website
http://mzmatch.sourceforge.net/index.php

## Description
mzMatch.R is designed for LC-MS preprocessing and has integration with XCMS and the PeakML file format (which is designed to contain data from multiple chromatographic coupled MS runs). Initially features are detected in an xcmsSet with the centWave algorithm. The extracted peaks can then be visualised in PeakML files. Next biological/technical replicates are combined into a single sample. This stage includes the ability to filter by noise or RSD. Data from the sample experimental condition are then combined to allow for comparison between conditions and further filtering if desired. Retention time correction is provided by XCMS. There is also a blank filter tool that compares signal intensities between blanks and experimental samples. If the intensity of a feature is equal to or greater in a blank sample than an experimental sample, it is removed. Missing peaks can then be filled. Peaks that are not detected in at least 6 samples can then be filtered with the simple filter function. A dilution trend filter can also be applied. Groups of related peaks can then be clustered (isotopic peaks, fragments, adducts and multiply charged molecules). Peaks can then be annotated using user defined lists of metabolites. It also provides the functionality of isotopic labelling analysis. Peaks must be extracted from  LC-MS raw data using XCMS and then alignment, normalisation and filling in missing peaks must be performed with mzMatch.R, to produce a combined PeakML file. For targeted profiling a user defined, tab separated file of compounds of interest must also be provided (this list can also contain adducts and/or fragments). For untargeted profiling either all peaks can be searched for isotopes, databases such as KEGG or HMDB can be used to search for compounds or common biotransformations can be used to search for isotopes. For both isotopic profiling techniques, two files are produced a PDF and a tab-separated text file. Each page of the PDF contains an identified compound, along with its polarity, mass, etc., as well as graphs detailing each chromatograph and labelling patterns. MetAssign is a probabilistic Putative Metabolite Annotation algorithm implemented in mzMatch that assigns posterior probabilities to the likelihood of the annotation. A Bayesian Markov Chain Monte Carlo sampling scheme is used to simultaneously group features and assign molecular formulas to the groups. Within a group, an individual peak is assigned an isotope-adduct pair. The cluster model is a mixture model with a Dirichlet process prior, so that the number of different metabolites does not need to be assigned as a prior. To be clustered features must have similar retention times, masses explainable by a calculated isotope/ adduct and the correct intensity relationships. Following each iteration of the Gibbs sampling scheme the posterior probability of the annotation is calculated. The more peaks that are assigned to a formula, the more likely that it is the correct annotation.

## Functionality
- Preprocessing
- Annotation/MS/Level 3 - Tentative Candidates

## Instrument Data Type
- LC-MS

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
R, Java

## Dependencies
R (≥ 2.15.3), xcms, multtest, mzR, rJava, XML, snow, caTools, bitops, ptw, gplots, tcltk2, JRE ≥ 7

## Input Formats - Open
mzData, mzML, mzXML

## Input Formats - Proprietary
N/A

## Published
2011

## Last Updated
2015

## License
LGPL-2

## Paper
http://www.ncbi.nlm.nih.gov/pubmed/21401061

## PMID
21401061
