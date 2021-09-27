# TITLE: FAIR Maturity Indicator MI-R1.3-d2c4887a02-BIO_BACKGROUND_SIGNAL

## Authors: 
Ammar Ammar, ORCID:0000-0002-8399-8990

#### Publication Date: 2021-09-08
#### Last Edit: 2021-09-27
#### Accepted: pending

### Maturity Indicator Identifier: [MI-R1.3-d2c4887a02-BIO_BACKGROUND_SIGNAL](https://w3id.org/nsdra/maturity-indicator/readme/MI-R1.3-d2c4887a02-BIO_BACKGROUND_SIGNAL)

This maturity indicator falls under the FAIR principle R1.3:
(meta)data meet domain-relevant community standards

The ID of this MI is composed of the following segments (separated by hyphen):
1. Acronym for "Maturity Indicator"
1. The FAIR principle this maturity indicator belongs to
1. The first 10 characters truncated from the SHA-256 hash of the primary reference DOI of this maturity indicator.
1. A short name to distinguish the maturity indicator definition file

This MI is to indicate if the "cell/tissue background signal" is reported by the nano toxicity study data or not.

### Maturity Indicator Name:  The cell/tissue background signal is reported by the nano toxicity study

This maturity indicator is extracted from the following paper 
**Title:** Minimum information reporting in bioâ??nano experimental literature
**REF:** https://doi.org/10.1038/s41565-018-0246-4

### To which principle does it apply?  
R1.3

### What is being measured?
If the cell/tissue background signal is reported by the nano toxicity study data or not.

### Why should we measure it?
The background signal in the absence of particles, using whichever signalling modality to detect particles, should be quantified and reported. This is an important, often neglected, control that is essential for quantitative analysis across a variety of modalities (for example, flow cytometry, microscopy or magnetic resonance imaging).

### What must be provided for the measurement?
If the value is measured and reported in the data, the following field(s) should appear in JSON-LD metadata: 

| Field Name         | Alternative terms                        |
| ------------------ | ---------------------------------------- |
| background signal  | background-signal,<br>background_signal  |

### How is the measurement executed?
The "background signal" should be provided in a machine-readable format (JSON-LD) which can be queried using open universal protocol like HTTP.

### What is/are considered valid result(s)?
The presence of the field "background signal" in the JSON-LD metadata means the measurement is reported which is the valid result.

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
 			"name": "background signal"
 		}
 	]
 }
```

### Comments

