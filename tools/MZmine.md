# MZmine
Version: 2.31

## Website
http://mzmine.github.io/

## Description	
MZmine provides a toolkit of modules for MS data analysis. It now includes modules for: raw data import, raw data processing, peak detection, peak list alignment, peak identification, visualisation, normalisation and statistical analysis. It is able to process profile, centroid and MSn data. There are a number of different algorithms for peak detection: Local maxima - which detects the local maxima of the spectrum, Recursive threshold - which reduces false positive by not detecting noise peaks, Wavelet transform - which processing each spectra by matching them to the Mexican hat wavelet model using continuous wavelet transformation, Exact Mass - for high quality spectra, which uses FWHM to determine the centre of each peak, Centroid - for centroided data, which detects all peaks above a specified noise level and GridMass. There is an optional filter for FT-ICR-MS data that builds a theoretical model (Gaussian or Lorentzian) with a given mass resolution around each peak and removes noise below this model. After this m/z features are connected into a chromatograph. Individual peaks are then deconvoluted with a number of algorithms provided for this purpose: Baseline cut-off - peaks must have intensity and time spans over given ranges, Noise amplitude - the same as Baseline cut-off but the baseline is initially set to the level where the noise is most concentrated and Local minimum search identifies the local minima as the borders between peaks. There is an extra module that allows the noisy deconvoluted data to be fit to an ideal peak model. For alignment the RANSAC (random sample consensus) algorithm is used. It uses the RANSAC and alignment windows, consisting of the same m/z threshold but different rt thresholds. A scatterplot of all candidate alignments is made and the RANSAC algorithm is used to build a candidate model of alignment. LOESS is then applied and the correct retention time shift is predicted and then the peaks are then joined. The old Join aligner algorithm is also available. A number of options are then available: missing data filling, isotope detection, filtering and normalisation. For peak annotation, CAMERA can be used. Peaks can either be identified via a custom database or by searching online databases (PubChem, KEGG, METLIN, HMDB, ChemSpider, PlantCyc, LipidMaps and MassBank all directly interface with MZmine). NIST can also be directly interfaced. For statistical analysis a number of options are available: PCA, clustering, heatmaps, curvilinear distance analysis (CDA), Sammon's Projection and Log Ratio Plots. GridMass is a new feature detection algorithm for HRLC-MS data. LC-MS data can be represented on a 2D plot of m/z against retention time, with colour matching intensity. A grid of equally spaced probes is generated to cover the entire area. Each probe then finds the local maximum and it is then moved to this location to search for a higher intensity value. This process is repeated until no higher value can be detected, and the current probe location is then marked as a peak.

## Functionality	
- Workflow

## Instrument Data Type	
- MS/LC-MS/LC-MS/MS 
- MS/CE-MS
- MS/GC-MS

## Approaches	
- Untargeted

## Computer Skills	
Medium

## Software Type	
Toolkit

## Interface	
Graphical User Interface

## Operating System (OS)	
- Unix/Linux
- Mac OS
- Windows

## Language	
Java, R

## Dependencies 	
JRE ≥ 1.7, R, Rserve, ptw, gplots, baseline, hyperSpec, ggplot2, xcms, CAMERA, PROcess

## Input Formats - Open	
mzData, mzML, mzXML, netCDF

## Input Formats - Proprietary	
Thermo Fisher Scientific .raw, waters .raw, Aglient .csv

## Published	
2005

## Last Updated
2018

## License	
GPL-2

## Paper	
http://www.ncbi.nlm.nih.gov/pubmed/20650010

## PMID
20650010