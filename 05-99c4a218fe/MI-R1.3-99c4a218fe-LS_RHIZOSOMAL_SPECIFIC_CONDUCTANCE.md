# TITLE: FAIR Maturity Indicator MI-R1.3-99c4a218fe-LS_RHIZOSOMAL_SPECIFIC_CONDUCTANCE

## Authors: 
Ammar Ammar, ORCID:0000-0002-8399-8990

#### Publication Date: 2021-02-15
#### Last Edit: 2024-04-13
#### Accepted: pending

### Maturity Indicator Identifier: [MI-R1.3-99c4a218fe-LS_RHIZOSOMAL_SPECIFIC_CONDUCTANCE](https://w3id.org/nsdra/maturity-indicator/readme/MI-R1.3-99c4a218fe-LS_RHIZOSOMAL_SPECIFIC_CONDUCTANCE)

This maturity indicator falls under the FAIR principle R1.3:
(meta)data meet domain-relevant community standards

The ID of this MI is composed of the following segments (separated by hyphen):
1. Acronym for "Maturity Indicator"
1. The FAIR principle this maturity indicator belongs to
1. The first 10 characters truncated from the SHA-256 hash of the primary reference DOI of this maturity indicator.
1. A short name to distinguish the maturity indicator definition file

This MI is to indicate if specific conductance of the rhizosomal system (in liquid-surface exposure scenarios) is reported by the nano toxicity study data or not.

### Maturity Indicator Name:  The specific conductance of the rhizosomal system (in liquid-surface exposure scenarios) is reported by the nano toxicity study.

This maturity indicator is extracted from the following paper 
**Title:** Harmonizing Across Environmental Nanomaterial Testing Media for Increased Comparability of Nanomaterial Datasets
**DOI:** https://doi.org/10.1039/C9EN00448C

### To which principle does it apply?  
R1.3

### What is being measured?
If the specific conductance of the rhizosomal system (in liquid-surface exposure scenarios) is reported by the nano toxicity study data or not.

### Why should we measure it?
Specific conductance affects NM (homo- and hetero-) aggregation and deposition.

### What must be provided for the measurement?
If the value is measured and reported in the data, the following field(s) should appear in JSON-LD metadata: 

| Field Name                        | Alternative terms                                                                                                              |
| --------------------------------- | ------------------------------------------------------------------------------------------------------------------------------ |
| rhizosomal system specific conductance | rhizosomal_system_specific_conductance,<br>rhizosomal-system-specific-conductance,<br>RhizosomalSystemSpecificConductance |

### How is the measurement executed?
The "rhizosomal system specific conductance" should be provided in a machine-readable format (JSON-LD) which can be queried using open universal protocol like HTTP.

### What is/are considered valid result(s)?
The presence of the field "rhizosomal system specific conductance" in the JSON-LD metadata means the measurement is reported which is the valid result.

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
 			"name": "rhizosomal system specific conductance"
 		}
 	]
 }
```

### Comments

