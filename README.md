Migration-Data 
==============
Data files required for migration

## Editing ontology(obo format only)
+ This repository manages [dictyBase](https://dictycr.org) ontologies through
  the `ontologies` folder.
+ All ontologies are edited through pull request. Ontologies validated and
  merged through pull requests are automatically converted to
  [obograph-json](https://github.com/geneontology/obographs) formatted and
  commited to `obograph-json` folder. Ontologies converted to `obobgraph-json`
  format are __only__ loaded to the database. 
+ Any ontology commited without any pull requested therefor __will never be__
  loaded to the database. 


