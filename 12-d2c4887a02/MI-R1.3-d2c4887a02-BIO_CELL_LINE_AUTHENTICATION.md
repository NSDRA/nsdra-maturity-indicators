# TITLE: FAIR Maturity Indicator MI-R1.3-d2c4887a02-BIO_CELL_LINE_AUTHENTICATION

## Authors: 
Ammar Ammar, ORCID:0000-0002-8399-8990

#### Publication Date: 2021-09-08
#### Last Edit: 2021-09-27
#### Accepted: pending

### Maturity Indicator Identifier: [MI-R1.3-d2c4887a02-BIO_CELL_LINE_AUTHENTICATION](https://w3id.org/nsdra/maturity-indicator/readme/MI-R1.3-d2c4887a02-BIO_CELL_LINE_AUTHENTICATION)

This maturity indicator falls under the FAIR principle R1.3:
(meta)data meet domain-relevant community standards

The ID of this MI is composed of the following segments (separated by hyphen):
1. Acronym for "Maturity Indicator"
1. The FAIR principle this maturity indicator belongs to
1. The first 10 characters truncated from the SHA-256 hash of the primary reference DOI of this maturity indicator.
1. A short name to distinguish the maturity indicator definition file

This MI is to indicate if the "cell line authentication" is reported by the nano toxicity study data or not.

### Maturity Indicator Name:  The cell line authentication is reported by the nano toxicity study

This maturity indicator is extracted from the following paper 
**Title:** Minimum information reporting in bioâ??nano experimental literature
**REF:** https://doi.org/10.1038/s41565-018-0246-4

### To which principle does it apply?  
R1.3

### What is being measured?
If the cell line authentication is reported by the nano toxicity study data or not.

### Why should we measure it?
Two central challenges for cell culture experimentation are choosing a cell line to represent the biology of interest and ensuring that the desired cell line is actually used. Cell line authentication is vital and should be performed regularly, either by a trusted supplier or the individual laboratory. Additionally, passage number and evidence that a culture is free of mycoplasma should be provided, as both parameters substantially alter the behaviour of cells in culture. If an experiment is conducted with a â??standardâ?? cell line (for example, one for which American Type Culture Collection guidelines exist), the name and reference of the cell line should be provided. For primary cells, known details of donors should be provided, including number of donors, species, age and sex. Finally, cell cycle effects should be considered, as they can have a significant effect on cellular response.

### What must be provided for the measurement?
If the value is measured and reported in the data, the following field(s) should appear in JSON-LD metadata: 

| Field Name                | Alternative terms                                       |
| ------------------------- | ------------------------------------------------------- |
| cell line authentication  | cell-line-authentication,<br>cell_line_authentication   |

### How is the measurement executed?
The "cell line authentication" should be provided in a machine-readable format (JSON-LD) which can be queried using open universal protocol like HTTP.

### What is/are considered valid result(s)?
The presence of the field "cell line authentication" in the JSON-LD metadata means the measurement is reported which is the valid result.

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
 			"name": "cell line authentication"
 		}
 	]
 }
```

### Comments

