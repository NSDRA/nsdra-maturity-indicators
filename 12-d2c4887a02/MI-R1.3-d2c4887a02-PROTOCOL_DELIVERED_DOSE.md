# TITLE: FAIR Maturity Indicator MI-R1.3-d2c4887a02-PROTOCOL_DELIVERED_DOSE

## Authors: 
Ammar Ammar, ORCID:0000-0002-8399-8990

#### Publication Date: 2021-09-08
#### Last Edit: 2021-09-27
#### Accepted: pending

### Maturity Indicator Identifier: [MI-R1.3-d2c4887a02-PROTOCOL_DELIVERED_DOSE](https://w3id.org/nsdra/maturity-indicator/readme/MI-R1.3-d2c4887a02-PROTOCOL_DELIVERED_DOSE)

This maturity indicator falls under the FAIR principle R1.3:
(meta)data meet domain-relevant community standards

The ID of this MI is composed of the following segments (separated by hyphen):
1. Acronym for "Maturity Indicator"
1. The FAIR principle this maturity indicator belongs to
1. The first 10 characters truncated from the SHA-256 hash of the primary reference DOI of this maturity indicator.
1. A short name to distinguish the maturity indicator definition file

This MI is to indicate if the "delivered dose" is reported by the nano toxicity study data or not.

### Maturity Indicator Name:  The delivered dose is reported by the nano toxicity study

This maturity indicator is extracted from the following paper 
**Title:** Minimum information reporting in bioâ??nano experimental literature
**REF:** https://doi.org/10.1038/s41565-018-0246-4

### To which principle does it apply?  
R1.3

### What is being measured?
If the delivered dose is reported by the nano toxicity study data or not.

### Why should we measure it?
The amount of material that reaches the site or organ of interest is an essential piece of information. As in culture systems, there are multiple choices for the dose metric used, including percentage of injected dose delivered (%ID) and percentage of injected dose delivered per gram of organ (%ID gâ??1). Because of the diversity of bioâ??nano research, we recommend that sufficient information is provided to calculate the most common in vivo dosage metrics. Specifically, we recommend that the delivered dose is reported as the percentage of injected dose delivered per gram of tissue (%ID gâ??1). Normalizing in this way allows for more direct comparison of data from different organ systems and animals. Additionally, data on weight of organs or tissues measured (and used during normalization), and information on mass of material injected should be included to allow other researchers to calculate alternative metrics (for example; %ID, mg kgâ??1). If possible, in the cases of a nanocarrier, distinguishing between carrier delivery and cargo/drug delivery is desirable. Finally, consideration of the pharmacokinetics of the material under investigation is an important part of quantifying efficacy of potential nanomedicines.

### What must be provided for the measurement?
If the value is measured and reported in the data, the following field(s) should appear in JSON-LD metadata: 

| Field Name      | Alternative terms                     |
| --------------- | ------------------------------------- |
| delivered dose  | delivered-dose,<br>delivered_dose     |

### How is the measurement executed?
The "delivered dose" should be provided in a machine-readable format (JSON-LD) which can be queried using open universal protocol like HTTP.

### What is/are considered valid result(s)?
The presence of the field "delivered dose" in the JSON-LD metadata means the measurement is reported which is the valid result.

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
 			"name": "delivered dose"
 		}
 	]
 }
```

### Comments

