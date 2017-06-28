# MIDAS
``` diff
- Deprecated
```
Version: 1.1

## Website
http://midas.omicsbio.org/

## Description
Metabolite Identification via Database Searching (MIDAS) is a database searching tool for metabolite identification of LC-MS/MS data acquired from high resolution mass spectrometers (TOF, Orbitrap). The MetaCyc database or a custom database of metabolites can be searched to find metabolite matches. For metabolite-spectrum match (MSM) evaluation a three-level fragmentation tree is calculated for the candidate metabolite. Firstly the measured precursor m/z is compared to the database to find candidate matches. The first level fragmentation tree is then generated and traversed by depth-first search (DFS). When a fragment is generated three charged forms are considered: [F]+, [F+H]+ and [F+H]2+ (and opposite in negative ion mode). The m/z of the fragment is generated and its plausibility is calculated. MSM are scored by comparing the observed spectrum to the calculated spectrum using a modified dot function. Candidates are ranked by their MSM scores.

## Functionality
- Annotation

## Instrument Data Type
- Annotation/MS/Level 2a - Library Spectrum Match

## Approaches
- MS/LC-MS/LC-MS/MS

## Computer Skills
Basic

## Software Type
- Web Based

## Interface
- Web User Interface

## Operating System (OS)
- Unix/Linux
- Mac OS
- Windows

## Language
Python

## Dependencies
N/A

## Input Formats - Open
.mzML, .ft2

## Input Formats - Proprietary
N/A

## Published
2014

## Last Updated
2014

## License

## Paper
http://www.ncbi.nlm.nih.gov/pubmed/25157598

## PMID
25157598
