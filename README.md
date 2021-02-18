[![Build Status](https://travis-ci.com/globalbioticinteractions/template-dataset.svg)](https://travis-ci.com/globalbioticinteractions/template-dataset) [![DOI](https://zenodo.org/badge/26293374.svg)](https://zenodo.org/badge/latestdoi/26293374) [![GloBI](https://api.globalbioticinteractions.org/interaction.svg?accordingTo=globi:globalbioticinteractions/template-dataset)](https://globalbioticinteractions.org/?accordingTo=globi:globalbioticinteractions/template-dataset) 

This repository provides co-roosting interactions from the paper [Willoughby et al. 2017](https://www.mdpi.com/1424-2818/9/3/35) for integration into Global Biotic Interactions (GloBI, http://globalbioticinteractions.org) .

4. Edit your ```globi.json``` to provide a machine readable description of your dataset (e.g. citation, license, version, files, format).



term | example | description | 
--- | --- | ---
argumentTypeId | https://en.wiktionary.org/wiki/refute | a URI that points to a definition of how this records support, refutes or provides other kind of arguments in the context of described interaction. When unspecified, the argument is assumed to be in support of the documented interaction claim.
 argumentTypeName | refute | a human readable name that qualifies whether the record is in support or refutes of a particular interaction
sourceOccurrenceId | 83742b5e-f0fd-4c12-a0af-c97191ea7722 | globally unique id to reference the individual originating organism, specimen. Inspired by http://rs.tdwg.org/dwc/terms/#occurrenceID .
 sourceTaxonId | EOL:328583 | taxon classification id of originating organism in some taxon name authority
 sourceTaxonName | Enhydra lutris  | scientific name of taxon classification of originating organism 
 sourceBodyPartId | http://purl.obolibrary.org/obo/UBERON_0000178 | identifier of description of source body part is interacted with
 sourceBodyPartName | blood | human readable description of source body part (e.g., "blood", "fruit")
 sourceLifeStageId | http://purl.obolibrary.org/obo/UBERON_0007023 | identifier of description of source life stage
 sourceLifeStageName | adult | human readable description of source life stage (e.g., "adult", "juvenile")
 sourcePhysiologicalStateId | http://purl.obolibrary.org/obo/PATO_0001422 | identifier of description of source physiological state
 sourcePhysiologicalStateName | dead | human readable description of source physiological state (e.g., "dead", "rotten")
 interactionTypeId | RO:0002470 | id of interaction as described by the [OBO Relations Ontology](https://github.com/oborel/obo-relations)
 interactionTypeName | eats | human readable description of interactions
 targetOccurrenceId | a5ee64b5-081b-4fff-8adc-2b0c74b1f40a | globally unique id to reference the individual target organism, specimen. Inspired by http://rs.tdwg.org/dwc/terms/#occurrenceID .
 targetTaxonId |  EOL:1971 | taxon classification id of target organism. 
 targetTaxonName | Echinoidea | scientific name of taxon classification of target organism of interaction
 targetBodyPartId | http://purl.obolibrary.org/obo/UBERON_0000178 | identifier of description of target body part is interacted with
 targetBodyPartName | Echinoidea | human readable description of target body part (e.g., "blood")
 targetLifeStageId | http://purl.obolibrary.org/obo/UBERON_0007023 | identifier of description of target life stage
 targetLifeStageName | adult | human readable description of target life stage (e.g., "adult", "juvenile")
 targetPhysiologicalStateId | http://purl.obolibrary.org/obo/PATO_0001422 | identifier of description of target's phyiological state
 targetPhysiologicalStateName | dead | human readable description of target's physiological state (e.g., "dead", "rotten")
 localityId | GEONAMES:5391961 | reference to geo classification like geonames.org, gazetteer or other.
 localityName | San Francisco Bay, California, USA | human readable description of locale
 decimalLatitude | -41.0983423 | latitude of geographic center of interaction observation location http://rs.tdwg.org/dwc/terms/index.htm#decimalLatitude
 decimalLongitude | -121.1761111 | longtide of geographic center of interaction observation location http://rs.tdwg.org/dwc/terms/index.htm#decimalLongitude
 observationDateTime | 2014-11-18T06:37:04Z | [ISO 8601](https://en.wikipedia.org/wiki/ISO_8601) formatted date time string 
 referenceDoi | doi:10.1126/science.200.4340.403 | Digital Object Id (DOI, http://doi.org) is commonly used to give papers, datasets or other digital object a permanent id
 referenceUrl | http://eol.org/data_objects/13596344 | some resolvable url that point to information related to species interaction record
 referenceCitation| C. A. Simenstad, J. A. Estes, K. W. Kenyon, Aleuts, sea otters, and alternate stable-state communities, Science 200:403-411, from p. 404 (1978). | human readable reference 

## Term Id Sources
Rather than only supplying a name for a taxon and/or locality, a reference to some established taxonomy and/or geo database is preferred. Commonly used taxon id sources include, but are not limited to [GBIF](http://gbif.org), [EOL](http://eol.org),  [ITIS](http://itis.gov) and [WoRMS](http://marinespecies.org). Geo database or vocabularies include [geonames](http://geonames.org) and [Gazetteer Ontology](http://bioportal.bioontology.org/ontologies/GAZ).
 
## Interaction Id Cheatsheet

For more terms, please see [OBO Relations Ontology](https://github.com/oborel/obo-relations).
 
interactionTypeId | interactionTypeName 
--- | ---
[RO:0002470](http://www.ontobee.org/browser/rdf.php?o=RO&iri=http://purl.obolibrary.org/obo/RO_0002470) | eats
[RO:0002444](http://www.ontobee.org/browser/rdf.php?o=RO&iri=http://purl.obolibrary.org/obo/RO_0002444) | parasite of
[RO:0002455](http://www.ontobee.org/browser/rdf.php?o=RO&iri=http://purl.obolibrary.org/obo/RO_0002455) | pollinates
[RO:0002556](http://www.ontobee.org/browser/rdf.php?o=RO&iri=http://purl.obolibrary.org/obo/RO_0002556) | pathogen of
