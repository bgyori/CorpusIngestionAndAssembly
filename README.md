# Corpus Ingestion and Assembly
General information about the WorldModelers repos related to reading and assembly

## Reading and Assembly Software Components

This section describes the machine reading and assembly repositories.

### Eidos

Eidos is the machine reading system developed by the CLU lab at University of Arizona. This repository includes the reading software as well as code for integrating with DART.

- Repository: https://github.com/clulab/eidos
- License: While we will soon be licensed as Apache, currently one dependency has a GPL license. This will be removed very soon and the license will be updated.
- Documentation: https://github.com/clulab/eidos/wiki
- Stable version: https://github.com/clulab/eidos/releases/tag/julyEmbedBYOD is the most recent version used "in production".
- Versions available on Maven Central:
  - Older versions are at https://mvnrepository.com/artifact/org.clulab/eidos.
  - Newer versions are at http://artifactory.cs.arizona.edu:8081/artifactory/webapp/#/artifacts/browse/tree/General/sbt-release/org/clulab/eidos_2.12.
  - This arrangement will be updated soon.

### Concept Discovery

This is the concept identification component, which is used by the ontology-in-a-day (OIAD) system.

- Repository: https://github.com/clulab/conceptdiscovery/
- License: 
- Documentation: https://github.com/clulab/conceptdiscovery/#readme
- Stable version: 
- Versions available on Maven Central: not yet

### HUME

Hume is BBN's machine reading system that extracts CAGs and supports the OIAD clustering. It leverages the following software
- Repository: https://github.com/BBN-E/Hume
- License: Apache
- Documentation: TODO
- Stable version: TODO 
- Versions available on Maven Central:

Text-Open contains Java and Python APIs for reading and writing BBN's SerifXML format, which is BBN's internal representation of documents and information.
- Repository: https://github.com/BBN-E/text-open
- License: Apache
- Documentation: TODO
- Stable version: TODO
- Versions available on Maven Central:

LearnIt is a tool for customizing Machine Readers (a.k.a., Information Extraction algorithms) with human in the loop. Within WM, we also use it as a pattern-based extractor for event extraction.
- Repository: https://github.com/BBN-E/LearnIt
- License: Apache
- Documentation: TODO
- Stable version: TODO
- Versions available on Maven Central:

NLPLingo is BBN's Deep Learning toolkit for event extraction and causal relation extraction.
- Repository: https://github.com/BBN-E/nlplingo
- License: Apache
- Documentation: TODO
- Stable version: TODO
- Versions available on Maven Central:

CSerif contains C/C++ code for pre-reading of texts into BBN's SerifXML format. We are working on open sourcing this.
- Repository: TODO
- License: TODO
- Documentation: TODO
- Stable version: TODO
- Versions available on Maven Central:

### Sofia

- Repository: 
- License: 
- Documentation: 
- Stable version: 
- Versions available on Maven Central:

### INDRA

- Repository: 
- License: 
- Documentation: 
- Stable version: 
- Versions available on Maven Central:

## Ontology

The reading and assembly software developed under World Modelers program share the same underlying ontology. The ontology is available in this repository: https://github.com/WorldModelers/Ontologies. Please see the project's [README](https://github.com/WorldModelers/Ontologies/blob/master/README.md) for details about the JSON format that the ontology uses, and usage information.
