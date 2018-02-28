# ProbMetab
Version: 1.0

## Website
http://labpib.fmrp.usp.br/methods/probmetab/

## Description
This package performs compound assignment on already peak grouped LC-MS data using bayesian modeling. It suggests using a combination of XCMS, CAMERA and mzMatch for data preprocessing. It provides the functionality to combine molecular ion by CAMERA annotation between acquision modes. A non-redundant set of molecular ion annotations can then be extracted. Included in the package is a database of compounds to reactions from KEGG (there is also the option a user importing their own compound to reaction database). If an assement of carbon offset is available this can be used to improve predictions. The likelihood of each mass to compound assignment is then calculated, using carbon isotope ratio information if available. The reactions between the identified metabolites are then codified. Analysis flux can also be incorporated at this stage. A reaction matrix can then be created from the annotated molecular ions and the database. The ratio between observed and theoretical isotope patterns is then calculated (if carbon labelling is available). The likelihood of each mass to compound assignment is then calculated using mass accuracy and isotopic pattern if available. The posterior probabilities are then calculated according to the model (using the Gibbs sampler). At this stage a table of identified metabolites can be exported as an R matrix. Identified metabolites are then mapped to pathways that can be visualised in cytoscape.

## Functionality
- Annotation/MS/Level 3 - Tentative Candidates

## Instrument Data Type
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
CAMERA, graph, RCytoscape, multtest, RcppAramadillo, hwriter, GeneNet, RCurl, XML, rjson

## Input Formats - Open
mzData, mzML, mzXML, netCDF

## Input Formats - Proprietary
N/A

## Published
2013

## Last Updated
2013

## License
GPL

## Paper
http://www.ncbi.nlm.nih.gov/pubmed/24443383

## PMID
24443383
