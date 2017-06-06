# MetaboHunter
Version: 1

## Website
http://www.nrcbioinformatics.ca/metabohunter/

## Description
This is a web-based server designed for automatic metabolite assignment of 1H NMR spectra. It includes three methods for metabolite identification: a novel scoring function, an iterative greedy selective approach designed to minimise the number of false positives whilst slightly increasing the number of false negatives and selection approaches with a user defined chemical drift to allow for the identification of metabolites from spectra obtained under slightly different conditions to the reference spectra. It also includes two reference libraries: 876 spectra from HMDB and 448 spectra from MMCD, that were manually curated. Spectra are first filtered for noise by setting a minimum intensity threshold. A metabolite is considered to be present if at least one of its peaks matches a reference peak at a significance score greater than a user defined threshold. The significance score is the total number of matched peaks/ total number of peaks + 1. It is designed to not favour metabolites with a greater number of peaks.

## Functionality
- Annotation/NMR

## Instrument Data Type
- NMR/1H NMR

## Approaches
-

## Computer Skills
Basic

## Software Type
Web App

## Interface
Web user interface

## Operating System (OS)
- Unix/Linux
- Mac OS
- Windows

## Language
PHP, Javascript, Perl

## Dependencies
N/A

## Input Formats - Open
List of Peaks with amplitutes, .txt

## Input Formats - Proprietary
N/A

## Published
2009

## Last Updated
2015

## License

## Paper
http://www.ncbi.nlm.nih.gov/pubmed/21999117

## PMID
21999117
