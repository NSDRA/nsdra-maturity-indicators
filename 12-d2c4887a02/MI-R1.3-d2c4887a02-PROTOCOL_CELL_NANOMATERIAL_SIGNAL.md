# TITLE: FAIR Maturity Indicator MI-R1.3-d2c4887a02-PROTOCOL_CELL_NANOMATERIAL_SIGNAL

## Authors: 
Ammar Ammar, ORCID:0000-0002-8399-8990

#### Publication Date: 2021-09-08
#### Last Edit: 2021-09-27
#### Accepted: pending

### Maturity Indicator Identifier: [MI-R1.3-d2c4887a02-PROTOCOL_CELL_NANOMATERIAL_SIGNAL](https://w3id.org/nsdra/maturity-indicator/readme/MI-R1.3-d2c4887a02-PROTOCOL_CELL_NANOMATERIAL_SIGNAL)

This maturity indicator falls under the FAIR principle R1.3:
(meta)data meet domain-relevant community standards

The ID of this MI is composed of the following segments (separated by hyphen):
1. Acronym for "Maturity Indicator"
1. The FAIR principle this maturity indicator belongs to
1. The first 10 characters truncated from the SHA-256 hash of the primary reference DOI of this maturity indicator.
1. A short name to distinguish the maturity indicator definition file

This MI is to indicate if the "cells signal with nanomatial" is reported by the nano toxicity study data or not.

### Maturity Indicator Name:  The cells signal with nanomatial is reported by the nano toxicity study

This maturity indicator is extracted from the following paper 
**Title:** Minimum information reporting in bioâ??nano experimental literature
**REF:** https://doi.org/10.1038/s41565-018-0246-4

### To which principle does it apply?  
R1.3

### What is being measured?
If the cells signal with nanomatial is reported by the nano toxicity study data or not.

### Why should we measure it?
In culture, particleâ??cell association is commonly assessed using the signal label intensity, percentage cellular association, or by estimating particles associated per cell. Percentage cell association or cell percentage is a metric that has long been used with high-throughput flow cytometry data, and it is useful for distinguishing between heterogeneous populations of cells (for example, in cell biology and immunology studies). However, percentage cellular association can be an unreliable metric for comparative interpretation of results in bioâ??nano studies. This is especially true when the signal from a single particle is less than the cell autofluorescence, or when comparing particles with different levels of fluorescence. Thus, if an in-culture experiment involves only a single cell type, we recommend that the number of particles associated per cell is estimated or that the signal intensity of cells with labelled particles is provided. For instance, if flow cytometry is used to measure cellâ??particle association, the mean fluorescence intensity of the channel the particle fluoresces in should be reported as a histogram or distribution of values. Researchers should also bear in mind that association is distinct from internalization, and a number of techniques have been developed to distinguish internalization from association or surface binding.

### What must be provided for the measurement?
If the value is measured and reported in the data, the following field(s) should appear in JSON-LD metadata: 

| Field Name                    | Alternative terms                                             |
| ----------------------------- | ------------------------------------------------------------- |
| cells signal with nanomatial  | cells-signal-with-nanomatial,<br>cells_signal_with_nanomatial |

### How is the measurement executed?
The "cells signal with nanomatial" should be provided in a machine-readable format (JSON-LD) which can be queried using open universal protocol like HTTP.

### What is/are considered valid result(s)?
The presence of the field "cells signal with nanomatial" in the JSON-LD metadata means the measurement is reported which is the valid result.

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
 			"name": "cells signal with nanomatial"
 		}
 	]
 }
```

### Comments

