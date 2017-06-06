# MRM-DIFF

## Website
http://prime.psc.riken.jp/Metabolomics_Software/MRM-DIFF/index.html

## Description
Multiple reaction monitoring-based differential (MRM-DIFF) allows for the analysis of lipidomics LC-MS MRM assays. It relies on pooled QC samples, for the LOES/cubic spline method. From all the pooled QC samples, one is chosen as a reference (this is the chromatograph whose gravity is closest to the midpoint). Using correlation optimized warping (COW), all other chromatograms are aligned to this reference. A user defined library of retention time, MRM transitions and molecular formulas is used for metabolite identification and to estimate isotopes. A peak detection algorithm that uses the abundance of detected peaks for multivariate analysis is implemented. Isotopic peak abundance is resolved and signal intensity drifts are corrected using LOESS and cubic spline normalisation. Alternatively metabolite concentrations can be normalised to an internal standard. Peaks are detected by first finding the median amplitude (AF), first-order derivative (FF) and second-order derivative (SF) (the derivatives are calculated using Savitzky-Golay filter). The maximum amplitude difference between two adjacent peaks is detected, as well as the maxima between the first and second order derivatives. The edges of the peaks are recognised when the amplitude and first order derivative are both greater than AF and FF in two adjacent points and the tip is recognised when the sign of the first derivative changes and the second order derivative is less than SF. Metabolite identification is based on retention time accuracy. To calculate isotopic abundances and annotate peaks, the theoretical isotopic ratio of the molecular formula is calculated.

## Functionality
- Preprocessing

## Instrument Data Type
- MS/LC-MS/LC-QqQ-MS
- MS/LC-MS/LC-QqQ-MS/MS

## Approaches
- Lipidomics

## Computer Skills
Basic

## Software Type
Package

## Interface
Graphical User Interface

## Operating System (OS)
Windows

## Language
C#

## Dependencies
≥ .NET Famework 4.0, ≥4GB RAM

## Input Formats - Open
Reifycs .ABF, .mzML

## Input Formats - Proprietary
N/A

## Published

## Last Updated
2014

## License

## Paper
http://www.ncbi.nlm.nih.gov/pubmed/25688256

## PMID
25688256
