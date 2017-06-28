# TracMass2

## Website
http://pubs.acs.org/doi/suppl/10.1021/ac403905h

## Description
This software provides preprocessing of centroid LC-MS and GC-MS data. A tracking algorithm is used for the creation of pure ion chromatograms (PICs). First, PICs are assigned to every data point in the first scan then in the next scan PICs are assigned to data points by a greedy nearest neighbour strategy - if the m/z is sufficiently close to the PIC of the previous scan, the data point is assigned to the same PIC. For peak detection, each PIC is convolved with 2 zero area filters of different widths, with positions of maxima corresponding to peak locations. For each data point the noise level is estimated as the difference between the PIC and its smooth (smoothing is performed by convoluting with a Gaussian filter and weighting for standard deviation, which is also Gaussian but a different width). A correction factor is computed from the local estimate of noise and is used to prevent a too narrow filter from adapting to the noise. Next is the alignment procedure, which is split into 4 parts: clustering, warping, second clustering and generalised fuzzy Hough transform (GFHT) to resolve ambiguous clusters (which is optional). The peaks from all samples are scaled on the mass and time axis by their expected uncertainty and connected by Delaunay triangulation, with connections longer than 1 being removed. Remaining peaks are considered to belong to the same cluster. Clusters containing one peak are used as landmark peaks for warping. P-splines are fitted to the retention time deviations from the means of these clusters and retention times of all peaks are adjusted by retention time shifts from the warping algorithm. Clustering is then again performed. Finally GFHT is performed independently for each cluster. A GUI is provided for the inspection of raw data. The software is available to download in the paper's supporting information.

## Functionality
- Preprocessing

## Instrument Data Type
- MS/LC-MS/Centroid LC-MS
- MS/GC-MS

## Approaches
- Metabolomics/Untargeted

## Computer Skills
Advanced

## Software Type
- MATLAB Package

## Interface
- Command line interface

## Operating System (OS)
- Unix/Linux
- Mac OS
- Windows

## Language
MATLAB

## Dependencies
MATLAB (≥ R2010b)

## Input Formats - Open
mzData, mzML, mzXML, netCDF

## Input Formats - Proprietary
N/A

## Published
2010

## Last Updated
2014

## License
GPL (≥ 3)

## Paper
https://www.ncbi.nlm.nih.gov/pubmed/24611572

## PMID
24611572
