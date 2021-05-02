# TITLE: FAIR Maturity Indicator MI-R1.3-3ce932c4f9-SOLUBILITY

## Authors: 
Ammar Ammar, ORCID:0000-0002-8399-8990

#### Publication Date: 2021-02-24
#### Last Edit: 2021-05-03
#### Accepted: pending

### Maturity Indicator Identifier: [MI-R1.3-3ce932c4f9-SOLUBILITY](https://w3id.org/fair/maturity_indicator/terms/Gen2/MI-R1.3-3ce932c4f9-SOLUBILITY)

This maturity indicator falls under the FAIR principle R1.3:
(meta)data meet domain-relevant community standards

The ID of this MI is composed of the following segments (separated by hyphen):
1. Acronym for "Maturity Indicator"
1. The FAIR principle this maturity indicator belongs to
1. The first 10 characters truncated from the SHA-256 hash of the primary reference DOI of this maturity indicator.
1. A short name to distinguish the maturity indicator definition file

This MI is to indicate if nanomaterial's solubility is reported by the nano toxicity study data or not.

### Maturity Indicator Name:  The nanomaterial's solubility is reported by the nano toxicity study

This maturity indicator is extracted from the following paper 
**Title:** The Nanomaterial Registry: facilitating the sharing and analysis of data in the diverse nanomaterial community
**DOI:** http://dx.doi.org/10.2147/IJN.S40722

### To which principle does it apply?  
R1.3

### What is being measured?
If the nanomaterial's solubility is reported by the nano toxicity study data or not.

### Why should we measure it?
The degree to which a material can be dissolved in another material so that a single homogeneous, 
temporarily stable phase results. Expressed as the categorization of a material as hydrophilic or lipophilic as well as P value and D value.

### What must be provided for the measurement?
If the value is measured and reported in the data, the following field(s) should appear in JSON-LD metadata: 

| Field Name  | Alternative terms            |
| ----------- | ---------------------------- |
| solubility  | Solubility,<br>SOLUBILITY    |

### How is the measurement executed?
The nanomaterial's solubility should be provided in a machine-readable format (JSON-LD) which can be queried using open universal protocol like HTTP.

### What is/are considered valid result(s)?
The presence of the field "solubility" in the JSON-LD metadata means the measurement is reported which is the valid result.

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
 			"name": "solubility"
 		}
 	]
 }
```

### Comments

