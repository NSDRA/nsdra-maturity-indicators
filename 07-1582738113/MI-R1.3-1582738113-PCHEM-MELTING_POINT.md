# TITLE: FAIR Maturity Indicator MI-R1.3-1582738113-PCHEM-MELTING_POINT

## Authors: 
Ammar Ammar, ORCID:0000-0002-8399-8990

#### Publication Date: 2021-03-18
#### Last Edit: 2024-04-13
#### Accepted: pending

### Maturity Indicator Identifier: [MI-R1.3-1582738113-PCHEM-MELTING_POINT](https://w3id.org/nsdra/maturity-indicator/readme/MI-R1.3-1582738113-PCHEM-MELTING_POINT)

This maturity indicator falls under the FAIR principle R1.3:
(meta)data meet domain-relevant community standards

The ID of this MI is composed of the following segments (separated by hyphen):
1. Acronym for "Maturity Indicator"
1. The FAIR principle this maturity indicator belongs to
1. The first 10 characters truncated from the SHA-256 hash of the primary reference DOI of this maturity indicator.
1. A short name to distinguish the maturity indicator definition file

This MI is to indicate if "melting point" is reported by the nano toxicity study data or not.

### Maturity Indicator Name:  The melting point is reported by the nano toxicity study

This maturity indicator is extracted from the following paper 
**Title:** Globally Harmonized System of Classification and Labeling of Chemicals (GHS), UNECE
**REF:** https://unece.org/DAM/trans/danger/publi/ghs/ghs_rev07/English/01e_part1.pdf

### To which principle does it apply?  
R1.3

### What is being measured?
If the melting point is reported by the nano toxicity study data or not.

### Why should we measure it?
This is one of the nanomaterial's physiochemical propoerties that should be reported in teh SDS.
The SDS should provide a clear description of data used to identify the hazards.
 

### What must be provided for the measurement?
If the value is measured and reported in the data, the following field(s) should appear in JSON-LD metadata: 

| Field Name      | Alternative terms                   |
| --------------- | ----------------------------------- |
| melting point   | melting_point,<br>melting-point     |

### How is the measurement executed?
The "melting point" should be provided in a machine-readable format (JSON-LD) which can be queried using open universal protocol like HTTP.

### What is/are considered valid result(s)?
The presence of the field "melting point" in the JSON-LD metadata means the measurement is reported which is the valid result.

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
 			"name": "melting point"
 		}
 	]
 }
```

### Comments

