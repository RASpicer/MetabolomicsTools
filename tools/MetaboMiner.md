# MetaboMiner
Version: 1

## Website
http://wishart.biology.ualberta.ca/metabominer/

## Description
This performs semi-automated metabolite quantification of 2D TOCSY and HSQC spectra. It contains reference libraries split by biofluid: CSF, plasma and urine, as well as a biofluid library and a total library. There are 223 TOCSY spectra (from BMRB and MRMD) and 502 HSQC spectra (from HMDB). A number of peak processing methods are included: streak removal and symmetry editing. Streaks (usually residual solvent signals) are found and removed by finding groups of peaks at common locations and removing them. Symmetrical editing is for TOCSY spectra, as TOCSY peak signals form a symmetrical square pattern along the diagonal line, and thus off diagonal peaks without symmetry can be considered as artifacts. A metabolite is identified if it satisfies the minimum signature requirement - the minimum peak set that can uniquely identify a compound from all others in the library. The false positive rate is reduced by having a minimum number of matched peaks and a minimum fraction of peaks. There are two compound identification techniques: minimal signature method (MS) and percentage match method (PM).

## Functionality
- Annotation/NMR

## Instrument Data Type
- NMR/2D TOCSY NMR
- NMR/2D HSQC NMR

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
Java

## Dependencies
≥ JRE 5.0

## Input Formats - Open
List of peaks with optional amplitudes

## Input Formats - Proprietary
N/A

## Published
2008

## Last Updated
2008

## License

## Paper
https://www.ncbi.nlm.nih.gov/pubmed/19040747

## PMID
19040747
