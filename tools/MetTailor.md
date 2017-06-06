# MetTailor
Version: 2.0

## Website
https://sourceforge.net/projects/mettailor/

## Description
This is designed for use after initial peak picking and alignment but before statistical analysis. It provides dynamic block summarisation (DBS) to correct for peak misalignments and isotopic pattern validation to verify correct alignments. DBS is used to create blocks which capture a single compound, which is present in the majority or all samples. Each block is uniformly sized. A peak is considered well aligned if it is present above a given intensity, in above a threshold number of samples. A peak is missing if it not present/ below an intensity threshold. If a given block contains no well aligned peaks, DBS identifies a lead peak (sample with smallest number of missing data), if current block centre coincides with this peak, the peak is then marked as well aligned. If not the centre is then placed to the lead peak and repeated. A quantitative summary is then captured for each block from the peak apex or largest integrated peak area. This summary can then be used to correct misalignments, resulting in fewer missing data. There is then the option to extract isotopic patterns to ensure that the alignments are correct, by using natural isotope distributions. This involves determining the charge of the candidate compound and extracting the ratio between the monoisotopic and isotopic peaks. RT(delta)-based normalisation can be used to correct the effect of temporal factors. It uses the weighted sum of peak area values in the RT neighbourhood for normalisation. Alternatively total intensity sum (TIS) normalisation can be used (TIS is calculated and the data is rescaled to the TIS across all compounds).

## Functionality
- Preprocessing

## Instrument Data Type
- MS/GC-MS
- MS/LC-MS

## Approaches
-

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
R

## Dependencies
N/A

## Input Formats - Open
.txt/ .csv

## Input Formats - Proprietary
N/A

## Published
2015

## Last Updated
2015

## License
GPL (≥ 2)

## Paper
http://www.ncbi.nlm.nih.gov/pubmed/26220962

## PMID
26220962
