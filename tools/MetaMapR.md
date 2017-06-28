# MetaMapR
Version: 1.2.1

## Website
http://dgrapov.github.io/MetaMapR/

## Description
MetaMapR uses structural similarity, mass spectral similarity and empirical correlation information to generate metabolic networks from metabolomics data. It is able to fill in the missing gaps in the network using this extra biochemical information. Data can be inputted in over 200 biological database identifiers as the package CTSgetR is used to translate between different common chemical databases (CTSgetR is an R package which interfaces with the chemical translation system (CTS)). Optionally m/z and intensity pair strings can be uploaded to calculate empirical correlation relationships. Metabolites can be mapped to KEGG or PubChem CIDs to calculate biochemical similarity networks. Reaction networks are generated using substrate-product pair reactions from the KEGG RPAIR. PubChem substructure fingerprints are used to generate structural similarity networks using Tanimoto similarity. Cosine correlations are calculated pairwise between mass spectra to obtain the spectral similarity score. Pearson, biweight correlations and Spearman correlations between measure metabolite values are calculated to obtain empirical dependency networks. Results can then be exported to cytoscape.

## Functionality
- Pathway Analysis

## Instrument Data Type
-

## Approaches
-

## Computer Skills
- Medium
- Advanced

## Software Type
- Web App
- R Package

## Interface
- Web user interface
- Command line interface

## Operating System (OS)
- Unix/Linux
- Mac OS
- Windows

## Language
R, Twitter Bootstrap front-end, CSS, HTML, JavaScript

## Dependencies
Shiny

## Input Formats - Open
Peaklist .csv

## Input Formats - Proprietary
N/A

## Published
2014

## Last Updated
2015

## License
GPL-3

## Paper
http://www.ncbi.nlm.nih.gov/pubmed/25847005

## PMID
25847005
