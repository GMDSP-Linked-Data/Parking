Parking
==============

Modelling Parking Site data for the [Greater Manchester Data Synchronisation Programme][gmdsp]

[gmdsp]: http://gmdsp.org.uk/


Contents
----------
This repository contains:

- Generic Open Refine model, along with associated XML file/graph
- Sample RDF/XML & Graphs for each local authority
- Exported Open Refine projects for each local authority

To follow:

- Mapping file of source datasets
- Example/useful SPARQL queries


Parking ontology
------------------------
The GMDSP Parking ontology is hosted in a [dedicated GMDSP ontologies repostory][ont] 

[ont]: https://github.com/GMDSP-Linked-Data/ontologies


Data summary (23 Dec 2014)
---------------------------
From the four data sources, a total of 225 records were modelled.

This resulted in a total of 5,680 triples (facts) being published

| Dataset    | Records | Triples |
|------------|---------|---------|
| Manchester | 72      | 1,371   |
| Salford    | 9       | 208     |
| Stockport  | 117     | 3,532   |
| Tameside   | 27      | 569     |
| Trafford   | n/a     | n/a     |
| TOTALS     | 225     | 5,680   |

Live data
----------
Production data can be found at the GMDSP [QuadStore][quad]

[quad]: http://data.gmdsp.org.uk/themes


SPARQL endpoint
---------------
The GMDSP [SPARQL endpoint][sp] can be used to query the production datasets.

[sp]: http://data.gmdsp.org.uk/sparql
