# TITLE: FAIR Maturity Indicator MI-R1.3-324358ad68-I-COLLECTION_ORGANISMS

## Authors: 
Ammar Ammar, ORCID:0000-0002-8399-8990

#### Publication Date: 2021-03-17
#### Last Edit: 2024-04-13
#### Accepted: pending

### Maturity Indicator Identifier: [MI-R1.3-324358ad68-I-COLLECTION_ORGANISMS](https://w3id.org/nsdra/maturity-indicator/readme/MI-R1.3-324358ad68-I-COLLECTION_ORGANISMS)

This maturity indicator falls under the FAIR principle R1.3:
(meta)data meet domain-relevant community standards

The ID of this MI is composed of the following segments (separated by hyphen):
1. Acronym for "Maturity Indicator"
1. The FAIR principle this maturity indicator belongs to
1. The first 10 characters truncated from the SHA-256 hash of the primary reference DOI of this maturity indicator.
1. A short name to distinguish the maturity indicator definition file

This MI is to indicate if "collection organisms" information is reported by the nano toxicity study data or not.

### Maturity Indicator Name:  The collection organism information is reported by the nano toxicity study

This maturity indicator is extracted from the following paper 
**Title:** Best practice in reporting corona studies: minimum information about Nanomaterial Biocorona Experiments (MINBE)
**DOI:** https://doi.org/10.1016/j.nantod.2019.06.004

### To which principle does it apply?  
R1.3

### What is being measured?
If the collection organisms information is reported by the nano toxicity study data or not.

### Why should we measure it?
Collection organisms informations is important to report for corona characterization and
to maximize the ability cross-comparison with other reported studies. Information to report:
sex, age, growth condition, organism part, and any known genetic variations for the source of the biofluids.
If the samples were from a cell line, passage number, note cell line, source, and type.

### What must be provided for the measurement?
If the value is measured and reported in the data, the following field(s) should appear in JSON-LD metadata: 

| Field Name                | Alternative terms                                                        |
| ------------------------- | ------------------------------------------------------------------------ |
| collection organisms      | collection_organisms,<br>collection-organisms,<br>CollectionOrganisms    |

### How is the measurement executed?
The collection organisms should be provided in a machine-readable format (JSON-LD) which can be queried using open universal protocol like HTTP.

### What is/are considered valid result(s)?
The presence of the field "collection organisms" in the JSON-LD metadata means the measurement is reported which is the valid result.

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
 			"name": "collection organisms"
 		}
 	]
 }
```

### Comments

