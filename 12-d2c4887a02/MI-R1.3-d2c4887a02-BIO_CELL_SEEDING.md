# TITLE: FAIR Maturity Indicator MI-R1.3-d2c4887a02-BIO_CELL_SEEDING

## Authors: 
Ammar Ammar, ORCID:0000-0002-8399-8990

#### Publication Date: 2021-09-08
#### Last Edit: 2024-04-13
#### Accepted: pending

### Maturity Indicator Identifier: [MI-R1.3-d2c4887a02-BIO_CELL_SEEDING](https://w3id.org/nsdra/maturity-indicator/readme/MI-R1.3-d2c4887a02-BIO_CELL_SEEDING)

This maturity indicator falls under the FAIR principle R1.3:
(meta)data meet domain-relevant community standards

The ID of this MI is composed of the following segments (separated by hyphen):
1. Acronym for "Maturity Indicator"
1. The FAIR principle this maturity indicator belongs to
1. The first 10 characters truncated from the SHA-256 hash of the primary reference DOI of this maturity indicator.
1. A short name to distinguish the maturity indicator definition file

This MI is to indicate if the "cell seeding" is reported by the nano toxicity study data or not.

### Maturity Indicator Name:  The cell seeding is reported by the nano toxicity study

This maturity indicator is extracted from the following paper 
**Title:** Minimum information reporting in bioâ??nano experimental literature
**REF:** https://doi.org/10.1038/s41565-018-0246-4

### To which principle does it apply?  
R1.3

### What is being measured?
If the cell seeding is reported by the nano toxicity study data or not.

### Why should we measure it?
The number of cells present during an in-culture experiment is an essential parameter for determining cellular dose. Thus, the number of cells seeded, percentage confluency at the start of an experiment and time between seeding and experimentation should be reported for cell culture experiments. For experiments involving multiple cell types (for example, co-culture, tumour spheroids), the number of non-target (for example, healthy) cells and the number of target (for example, diseased) cells should be reported. Ideally, however, the number of cells for each cell type present should be reported. Additionally, incubator conditions should be reported, including temperature, humidity and CO2 percentage. Finally, details of whether replicates were performed in parallel, or as independent incubation experiments, should be provided.

### What must be provided for the measurement?
If the value is measured and reported in the data, the following field(s) should appear in JSON-LD metadata: 

| Field Name    | Alternative terms                 |
| ------------- | --------------------------------- |
| cell seeding  | cell-seeding,<br>cell_seeding     |

### How is the measurement executed?
The "cell seeding" should be provided in a machine-readable format (JSON-LD) which can be queried using open universal protocol like HTTP.

### What is/are considered valid result(s)?
The presence of the field "cell seeding" in the JSON-LD metadata means the measurement is reported which is the valid result.

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
 			"name": "cell seeding"
 		}
 	]
 }
```

### Comments

