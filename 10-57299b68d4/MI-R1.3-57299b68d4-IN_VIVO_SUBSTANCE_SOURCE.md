# TITLE: FAIR Maturity Indicator MI-R1.3-57299b68d4-IN_VIVO_SUBSTANCE_SOURCE

## Authors: 
Ammar Ammar, ORCID:0000-0002-8399-8990

#### Publication Date: 2021-03-02
#### Last Edit: 2024-04-13
#### Accepted: pending

### Maturity Indicator Identifier: [MI-R1.3-57299b68d4-IN_VIVO_SUBSTANCE_SOURCE](https://w3id.org/nsdra/maturity-indicator/readme/MI-R1.3-57299b68d4-IN_VIVO_SUBSTANCE_SOURCE)

This maturity indicator falls under the FAIR principle R1.3:
(meta)data meet domain-relevant community standards

The ID of this MI is composed of the following segments (separated by hyphen):
1. Acronym for "Maturity Indicator"
1. The FAIR principle this maturity indicator belongs to
1. The first 10 characters truncated from the SHA-256 hash of the primary reference DOI of this maturity indicator.
1. A short name to distinguish the maturity indicator definition file

This MI is to indicate if the test substance source is reported by the nano toxicity study data or not.

### Maturity Indicator Name:  The test substance source is reported by the nano toxicity study (in vivo)

This maturity indicator is extracted from the following paper 
**Title:** RiskGONE toxicity risk assessment quality measures
**Reference Website:** https://riskgone.eu

### To which principle does it apply?  
R1.3

### What is being measured?
If the test substance source is reported by the nano toxicity study data or not.

### Why should we measure it?
This is one of the quality measure that need to be reported by toxicity risk assessment experiments as decided in the RiskGONE EU project.

### What must be provided for the measurement?
If the value is measured and reported in the data, the following field(s) should appear in JSON-LD metadata: 

| Field Name                      | Alternative terms                                                |
| ------------------------------- | ---------------------------------------------------------------- |
| test substance source in-vivo   | test-substance-source-in-vivo,<br>test_substance_source_in_vivo  |

### How is the measurement executed?
The test substance source should be provided in a machine-readable format (JSON-LD) which can be queried using open universal protocol like HTTP.

### What is/are considered valid result(s)?
The presence of the field "test substance source in-vivo" in the JSON-LD metadata means the measurement is reported which is the valid result.

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
 		"url": "schema:url",
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
 			"name": "test substance source in-vivo"
 		}
 	]
 }
```

### Comments

