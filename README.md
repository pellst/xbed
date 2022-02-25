[![Build Status](https://travis-ci.org/pellst/xbed.svg?branch=master)](https://travis-ci.org/pellst/xbed)
[![DOI](https://zenodo.org/badge/13996/pellst/xbed.svg)](https://zenodo.org/badge/latestdoi/13996/pellst/xbed)

# Xenbase Experimental Data Ontology (XBED)

An ontology of entities and concepts used in the curation of experimental data by Xenbase the Model Organism Knowledgebase for Xenopus species.

## Subsets
The XBED contains several different subsets of datatypes shown below, classes may belong to multiple subsets.
### Antibody methods
Experimental methods making use of antibodies such as immunohistochemistry, western blot, ELISA or ChIP.
### Experimental Assay
Different types of assay used in an exepriment such as RNA-Seq, in-situ hybridization or EMSA.
### Article content types
Classifications for content type for use in curation, for example 'Gene expression' and 'Phenotype' This also encompasses licensing and access permissions for article content.
### Copyright access types
Primarily used for classes to distinguish accessibility of an article, includes creative commons license types.
### ChIP_type
Distinct types of ChIP assay, primarily used to distinguish between transcription factor and epigenetic targeting antibody based assays.
### GEO_assay_types
Sequencing based assay types associated with data from the NCBI's Gene Expression Omnibus data repository.
### GEO_manipulation_types
Classes which describe experimental manipulations which may be used in experiments associated with data from the NCBI's Gene Expression Omnibus data repository.
### Experimental Manipulation
Classes which describe experimental manipulations such as tissue ablation or mrNA microinjection.
### morpholino types
Distinct types of morpholino oligonucleotide such as photo morpholinos or splice blocking morpholinos.
### PHENO_assay_types
Assays used in curation of phenotype data in xenbase.
### XED copyright pmc subset
Creative Commons license types for articles coming from the NCBI's PubMed Central repository.
### XED Orthology prediction method
Classes for orthology methods used in DIOPT pipeline.
### XED Orthology prediction finding
Classes for statuses of DIOPT pipeline orthology methods

More information can be found at http://obofoundry.org/ontology/xbed

## Versions

### Stable release versions

The latest version of the ontology can always be found at:

http://purl.obolibrary.org/obo/xbed.owl

(note this will not show up until the request has been approved by obofoundry.org)

### Editors' version

Editors of this ontology should use the edit version, [src/ontology/xbed-edit.owl](src/ontology/xbed-edit.owl)

## Contact

Please use this GitHub repository's [Issue tracker](https://github.com/pellst/xbed/issues) to request new terms/classes or report errors or specific concerns related to the ontology.

## Acknowledgements

This ontology repository was created using the [ontology starter kit](https://github.com/INCATools/ontology-starter-kit)