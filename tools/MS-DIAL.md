# MS-DIAL
Version: 2.82

## Website
http://prime.psc.riken.jp/Metabolomics_Software/MS-DIAL/index.html

## Description
Provides deconvolution for untargeted data-independent acquisition (DIA) tandem MS data. Initially data are converted into the Analysis Base File (ABF) format, to allow for rapid data extraction. For peak detection, the peak detection algorithm first starts with a smoothing method (linearly weighted smoothing average, moving average, Savitzky-Golay or binomial filter) for retention time and accurate mass. Peaks are then detected by first finding the median amplitude (AF), first-order derivative (FF) and second-order derivative (SF) (the derivatives are calculated using Savitzky-Golay filter). The maximum amplitude difference between two adjacent peaks is detected, as well as the maxima between the first and second order derivatives. The edges of the peaks are recognised when the amplitude and first order derivative are both greater than AF and FF in two adjacent points and the tip is recognised when the sign of the first derivative changes and the second order derivative is less than SF. Two dimensional peak detection or peak spotting occurs by using retention time and accurate mass (MS1). Detected peak tops are displayed as spots, with spots of the same retention time and similar m/z being compared by peak height, to evaluate whether they should be merged or not. Each peak then undergoes deconvolution using the MS^2dec algorithm, which first extracts the product spectra for all precursor peaks on all MS/MS spectra (based on GC-MS deconvolution, but using accurate mass instead of nominal mass). Least squares optimisation is used to extract model peaks from chromatograms. Background noise and coeluted metabolites are removed by determining peak heights of reconstructed chromatograms. After smoothing, the chromatograph undergoes baseline correction by finding the local minimum of a user defined segment, calculating the median of all local minimums and discarding points above this value. Ideal slope and sharpness values are calculated, with an ideal slope of >0.95 required for a peak to be considered a model peak. Metabolites are identified using MassBank, LipidBlast, NIST or a custom list. Metabolite identifications are assigned a score based on similarity of MS/MS, MS1, RT and isotope ratio. Peak alignment is performed using an algorithm based on Joint Aligner in MZmine. Missing value imputation is also provided. Sequential windowed acquisition of all theoretical (SWATH) acquisition is a DIA approach, which was particularly used to test this software.

## Functionality
- Preprocessing

## Instrument Data Type
- MS/LC-MS/LC-MS/MS

## Approaches
- Untargeted

## Computer Skills
Advanced

## Software Type
Package

## Interface
- Command line interface
- Graphical user interface

## Operating System (OS)
Windows XP/Vista/7/8

## Language
C#

## Dependencies
≥ .NET Famework 4.0, ≥4GB RAM

## Input Formats - Open
.mzML

## Input Formats - Proprietary
Agilent .d, AB Sciex .wiff, Thermo Fisher Scientific .raw, Bruker Daltonics .d, waters .raw

## Published
2015

## Last Updated
2018

## License

## Paper
http://www.ncbi.nlm.nih.gov/pubmed/25938372

## PMID
25938372
