# TITLE: FAIR Maturity Indicator MI-R1.3-d2c4887a02-MAT-QUANTIFICATION

## Authors: 
Ammar Ammar, ORCID:0000-0002-8399-8990

#### Publication Date: 2021-09-08
#### Last Edit: 2024-04-13
#### Accepted: pending

### Maturity Indicator Identifier: [MI-R1.3-d2c4887a02-MAT-QUANTIFICATION](https://w3id.org/nsdra/maturity-indicator/readme/MI-R1.3-d2c4887a02-MAT-QUANTIFICATION)

This maturity indicator falls under the FAIR principle R1.3:
(meta)data meet domain-relevant community standards

The ID of this MI is composed of the following segments (separated by hyphen):
1. Acronym for "Maturity Indicator"
1. The FAIR principle this maturity indicator belongs to
1. The first 10 characters truncated from the SHA-256 hash of the primary reference DOI of this maturity indicator.
1. A short name to distinguish the maturity indicator definition file

This MI is to indicate if the nanomaterial "quantification of varied properties" is reported by the nano toxicity study data or not.

### Maturity Indicator Name:  The nanomaterial quantification of varied properties is reported by the nano toxicity study

This maturity indicator is extracted from the following paper 
**Title:** Minimum information reporting in bioâ??nano experimental literature
**REF:** https://doi.org/10.1038/s41565-018-0246-4

### To which principle does it apply?  
R1.3

### What is being measured?
If the nanomaterial quantification of varied properties is reported by the nano toxicity study data or not.

### Why should we measure it?
The characterization requirements we have outlined above are envisioned as a minimum information standard. That is, while we believe that providing the recommended information is necessary, it may be insufficient for certain investigations. There are many other physicochemical properties of interest that have been demonstrated to influence biological responses, and exploration of such properties represents a rich space of research. Whenever possible, researchers should quantify and report any varied properties. For instance, if investigating the influence of particle rigidity on cellular response, the rigidity for each particle system should be measured (for example, by colloidal-probe atomic force microscopy) and reported.

### What must be provided for the measurement?
If the value is measured and reported in the data, the following field(s) should appear in JSON-LD metadata: 

| Field Name                              |
| --------------------------------------- |
| quantification of varied properties     |

### How is the measurement executed?
The "quantification of varied properties" should be provided in a machine-readable format (JSON-LD) which can be queried using open universal protocol like HTTP.

### What is/are considered valid result(s)?
The presence of the field "quantification of varied properties" in the JSON-LD metadata means the measurement is reported which is the valid result.

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
 			"name": "quantification of varied properties"
 		}
 	]
 }
```

### Comments

