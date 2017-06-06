# FeatureFinderMetabo
Version: 2.1.0

## Website
http://ftp.mi.fu-berlin.de/pub/OpenMS/release-documentation/html/TOPP_FeatureFinderMetabo.html

## Description
This provides label-free quantification of metabolites of LC-MS data. It is available as part of OpenMS. There are two stages to the algorithm: mass trace detection and feature assembly. Each data set of peaks is sorted by decreasing intensity and peaks that are below a user-defined threshold are filtered. Each of the most intense peaks is then considered a potential seeding point for mass trace construction. Mass traces are features with a similar m/z, which occur in adjacent scans. The mass traces are extended along the retention time axis from the seeding point, in both directions. This results in more peaks with similar m/z being recruited into the mass trace, depending upon an intensity-weighted Gaussian model (that reflects that low-intensity peaks are less reliable than higher intensity peaks). The algorithm is aborted when a specified number of scans have been searched without finding an adequate peak. Once a peak has been added to a trace, it cannot be used as a seeding point or be added to another trace. At this stage the mass traces need to be separated, so that each trace only contains a single feature. LOWESS with a polynomial of degree 2 is used as a smoothing technique. It is then tested whether or not peaks are sufficiently separated in order to be considered separate peaks. If peaks need to be separated, the minima between the 2 chromatographic peaks is used as a splitting point. During feature assembly the aim is to find features originating from the same progenitor metabolite and to cluster these adducts. To identify isotopes a HiRes generated library of isotopic masses is used. A scoring function is used to assess how likely it is a set of mass traces are caused by the same metabolite based on precomputed mass difference distributions of potential metabolite compositions. A correlation similarity score is used to assess whether mass traces grouped by m/z are also compatible in their elution times (it must be at least 70% full width at half-maximum). For each hypothesis a combined score is calculated. To give preference to high intensity signals, the scores are weighted to peak area normalised by the total sum of mass traces. A list of features is then produced that should not contain multiple peaks for a single metabolite.

## Functionality
- Preprocessing

## Instrument Data Type
- MS/LC-MS/Centroid LC-MS

## Approaches
-

## Computer Skills
- Advanced
- Medium

## Software Type
Package

## Interface
- Command line interface
- Graphical User Interface

## Operating System (OS)
Unix/Linux

## Language
C++

## Dependencies
N/A

## Input Formats - Open
ConsensusXML, DTA, DTA2D, EDTA, featureXML, KROENIK, MGF, ms2, mzML, mzXML, mzData, PEPLIST, TSV

## Input Formats - Proprietary
fid/XMASS

## Published
2014

## Last Updated
2017

## License
Three-clause BSD license

## Paper
http://www.ncbi.nlm.nih.gov/pubmed/24176773

## PMID
24176773
