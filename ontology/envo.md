---
layout: ontology_detail
id: envo
contact:
  email: p.buttigieg@googlemail.com
  label: Pier Luigi Buttigieg
description: Ontology of environmental features and habitats
domain: environment
homepage: http://environmentontology.org/
page: https://github.com/EnvironmentOntology/envo
license:
  url: http://creativecommons.org/licenses/by/3.0/
  label: CC-BY
publications:
  - id: http://www.dx.doi.org/10.1186/2041-1480-4-43
    title: "The environment ontology: contextualising biological and biomedical entities"
products:
  - id: envo.owl
  - id: envo.obo
  - id: subsets/envo-basic.obo
    title: OBO-Basic edition of ENVO
  - id: subsets/EnvO-Lite-GSC.obo
    title: GSC Lite subset of ENVO
    homepage: http://environmentontology.org/downloads
title: Environment Ontology
dependencies:
 - id: uberon
 - id: pco
 - id: ro
 - id: chebi
 - id: ncbitaxon
jobs:
  - id: https://travis-ci.org/EnvironmentOntology/envo
    type: travis-ci
build:
  checkout: git clone https://github.com/EnvironmentOntology/envo.git
  email_cc: cjmungall@lbl.gov
  system: git
  path: .
  method: vcs
  infallible: 1
tracker: https://github.com/EnvironmentOntology/envo/issues/

---

EnvO is a community ontology for the concise, controlled description of environments.

<img src="/logos/envo.png"/>

Envo can be cited as:

Buttigieg, P. L., Morrison, N., Smith, B., Mungall, C. J., & Lewis, S. E. (2013). <b>The environment ontology: contextualising biological and biomedical entities</b>. <i>Journal of Biomedical Semantics, 4(1), 43</i>. <a href="http://www.dx.doi.org/10.1186/2041-1480-4-43">doi:10.1186/2041-1480-4-43</a>


