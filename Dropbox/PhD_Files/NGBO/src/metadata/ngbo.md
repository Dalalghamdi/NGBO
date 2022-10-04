---
layout: ontology_detail
id: ngbo
title: next generation biobanking ontology
jobs:
  - id: https://travis-ci.org/Dalalghamdi/next-generation-biobanking-ontology
    type: travis-ci
build:
  checkout: git clone https://github.com/Dalalghamdi/next-generation-biobanking-ontology.git
  system: git
  path: "."

description: next generation biobanking ontology is an open application ontology
representing omics contextual data

domain: stuff
homepage: https://github.com/Dalalghamdi/next-generation-biobanking-ontology
products:
  - id: ngbo.owl
  - id: ngbo.obo
contact:
 email: dal.alghamdi92@gmail.com
 label: Dalia Alghamdi
 github: dalalghamdi
 orcid: 0000-0002-2801-0767
dependencies:
 - id: ro
 - id: bfo
tracker: https://github.com/Dalalghamdi/next-generation-biobanking-ontology/issues
license:
  url: http://creativecommons.org/licenses/by/4.0/
=======
license: http://creativecommons.org/licenses/by/4.0/
  url: http://creativecommons.org/licenses/by/4.0/
  label: CC-BY
  usages:
- user: https://shgp.kacst.edu.sa/index.en.html
  description: Saudi Human Genome Program
  examples:
   - url: https://github.com/Dalalghamdi/NGBOSemanticWebApplication
     description: an ontology-based
web application for end-users with appropriate functions to discover and request the
specimen-derived data from SPARQL endpoints using a data federation approach

data-version: 2022-06-14
---

Enter a detailed description of your ontology here
