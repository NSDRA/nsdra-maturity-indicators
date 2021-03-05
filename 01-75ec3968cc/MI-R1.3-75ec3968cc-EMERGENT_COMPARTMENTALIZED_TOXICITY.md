# TITLE: FAIR Maturity Indicator MI-R1.3-75ec3968cc-EMERGENT_COMPARTMENTALIZED_TOXICITY

## Authors: 
Ammar Ammar, ORCID:0000-0002-8399-8990

#### Publication Date: 2021-02-26
#### Last Edit: 2021-03-05
#### Accepted: pending

### Maturity Indicator Identifier: [MI-R1.3-75ec3968cc-EMERGENT_COMPARTMENTALIZED_TOXICITY](https://w3id.org/fair/maturity_indicator/terms/Gen2/MI-R1.3-75ec3968cc-EMERGENT_COMPARTMENTALIZED_TOXICITY)

This maturity indicator falls under the FAIR principle R1.3:
(meta)data meet domain-relevant community standards

The ID of this MI is composed of the following segments (separated by hyphen):
1. Acronym for "Maturity Indicator"
1. The FAIR principle this maturity indicator belongs to
1. The first 10 characters truncated from the SHA-256 hash of the primary reference DOI of this maturity indicator.
1. A short name to distinguish the maturity indicator definition file

This MI is to indicate if the nanomaterial's compartmentalized toxicity is reported by the nano toxicity study data or not.

### Maturity Indicator Name:  The nanomaterial's compartmentalized toxicity is reported by the nano toxicity study

This maturity indicator is extracted from the following paper 
**Title:** Where Are We Heading in Nanotechnology Environmental Health and Safety and Materials Characterization?
**DOI:** https://doi.org/10.1021/acsnano.5b03496

### To which principle does it apply?  
R1.3

### What is being measured?
If the nanomaterial's compartmentalized toxicity is reported by the nano toxicity study data or not.

### Why should we measure it?
The nanomaterial's compartmentalized toxicity is one of the properties that, although dependent on intrinsic and extrinsic material properties, dynamically emerge 
at the nano-bio interface as the most proximate link to injury. These often reveals structure-activity relationships that can be 
used quantitatively for modeling and safer design.

### What must be provided for the measurement?
If the value is measured and reported in the data, the following field(s) should appear in JSON-LD metadata: 

| Field Name                    | Alternative terms                                          |
| ----------------------------- | ---------------------------------------------------------- |
| compartmentalized toxicity    | compartmentalized_toxicity,<br>compartmentalized-toxicity  |

### How is the measurement executed?
The "compartmentalized toxicity" field should be provided in a machine-readable format (JSON-LD) which can be queried using open universal protocol like HTTP.

### What is/are considered valid result(s)?
The presence of the field "compartmentalized toxicity" in the JSON-LD metadata means the measurement is reported which is the valid result.

### For which digital resource(s) is this relevant? (or 'all')
For nano toxicity related datasets.  

### Examples of good practices (that would score well on this assessment)
```{json}
{
 	"@context": {
 		"bs": "https://bioschemas.org/",
 		"schema": "https://schema.org/",
 		"citation": "schema:citation",
 		"name": "schema:name",
 		"url": "schema:name",
 		"variableMeasured": "schema:variableMeasured",
 		"unitText": "schema:unitText"
 	},
 	"@type": "schema:Dataset",
 	"name": "Dataset title",
 	"@id": "Dataset DOI",
 	"url": "Dataset URL",
 	"citation": "Dataset Citation/Publication",
 	"variableMeasured": [
 		{
 			"@type": "schema:PropertyValue",
 			"name": "compartmentalized toxicity"
 		}
 	]
 }
```

### Comments

