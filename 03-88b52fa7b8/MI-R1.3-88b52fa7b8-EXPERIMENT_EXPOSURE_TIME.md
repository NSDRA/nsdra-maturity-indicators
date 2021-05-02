# TITLE: FAIR Maturity Indicator MI-R1.3-88b52fa7b8-EXPERIMENT_EXPOSURE_TIME

## Authors: 
Ammar Ammar, ORCID:0000-0002-8399-8990

#### Publication Date: 2021-03-18
#### Last Edit: 2021-05-03
#### Accepted: pending

### Maturity Indicator Identifier: [MI-R1.3-88b52fa7b8-EXPERIMENT_EXPOSURE_TIME](https://w3id.org/fair/maturity_indicator/terms/Gen2/MI-R1.3-88b52fa7b8-EXPERIMENT_EXPOSURE_TIME)

This maturity indicator falls under the FAIR principle R1.3:
(meta)data meet domain-relevant community standards

The ID of this MI is composed of the following segments (separated by hyphen):
1. Acronym for "Maturity Indicator"
1. The FAIR principle this maturity indicator belongs to
1. The first 10 characters truncated from the SHA-256 hash of the primary reference DOI of this maturity indicator.
1. A short name to distinguish the maturity indicator definition file

This MI is to indicate if the experiment "exposure time" is reported by the nano toxicity study data or not.

### Maturity Indicator Name:  The experiment exposure time is reported by the nano toxicity study

This maturity indicator is extracted from the following paper 
**Title:** Metadata Stewardship in Nanosafety Research: Community-Driven Organization of Metadata Schemas to Support FAIR NanoScience Data
**REF:** https://doi.org/10.3390/nano10102033

### To which principle does it apply?  
R1.3

### What is being measured?
If the experiment exposure time is reported by the nano toxicity study data or not.

### Why should we measure it?
This is one of the nano particle's (NP) agglomeration-related metadata relevant for delivered dose (DD)
assessment as a means to facilitate correct interpretation of in vitro bioassays and support data reuse (case study value: 24 h).

### What must be provided for the measurement?
If the value is measured and reported in the data, the following field(s) should appear in JSON-LD metadata: 

| Field Name                 | Alternative terms                                     |
| -------------------------- | ----------------------------------------------------- |
| experiment exposure time   | experiment-exposure-time,<br>experiment_exposure_time |

### How is the measurement executed?
The "experiment exposure time" should be provided in a machine-readable format (JSON-LD) which can be queried using open universal protocol like HTTP.

### What is/are considered valid result(s)?
The presence of the field "experiment exposure time" in the JSON-LD metadata means the measurement is reported which is the valid result.

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
 			"name": "experiment exposure time"
 		}
 	]
 }
```

### Comments

