# EU-Ecolabel-laundry-detergent-product-criteria-ontology

This ontology is extracted from EU Eco-label laundry detergent criteria document (http://eur-lex.europa.eu/legal-content/EN/TXT/PDF/?uri=CELEX:32011D0264&from=EN).

It has been applied in a decision support process for EU Eco-labeling certification. (Xu, D., Karray, M. H., & Archimède, B. (2017). A semantic-based decision support platform to assist products’ eco-labeling process. Industrial Management & Data Systems, 117(7), 1340-1361.)

A Entity-Rule separation pattern is used to divide and modularize the ontology. 
laundry_detergent_criteria.owl is the entry of the whole ontology. 
Each laundry_detergent_criterion_x_xxx.owl records translated SWRL rules according to corresponding criterion in the document. 
didlist_1_saved_by_owlapi.owl is a modeling of Detergents Ingredients Database (http://ec.europa.eu/environment/ecolabel/documents/did_list/didlist_part_a_en.pdf and http://ec.europa.eu/environment/ecolabel/documents/did_list/didlist_part_b_en.pdf).
european_risk_phrases.owl records the code and statement of European Risk Phrases (https://en.wikipedia.org/wiki/List_of_R-phrases).
ghs_hazard_statement.owl records the code and statement of GHS Hazard Statement (https://en.wikipedia.org/wiki/GHS_hazard_statements).
The other owl files and modules are about some domain related terms which are still under development. 

We hope this ontology can be helpful to other similar projects, particularly, some ontology modules can be reused. 

Refinement and enrichment of current modules is undergoing. Development of other product groups of EU Eco-label is also in the plan.
