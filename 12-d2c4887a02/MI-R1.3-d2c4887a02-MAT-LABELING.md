# TITLE: FAIR Maturity Indicator MI-R1.3-d2c4887a02-MAT-LABELING

## Authors: 
Ammar Ammar, ORCID:0000-0002-8399-8990

#### Publication Date: 2021-08-08
#### Last Edit: 2021-09-27
#### Accepted: pending

### Maturity Indicator Identifier: [MI-R1.3-d2c4887a02-MAT-LABELING](https://w3id.org/nsdra/maturity-indicator/readme/MI-R1.3-d2c4887a02-MAT-LABELING)

This maturity indicator falls under the FAIR principle R1.3:
(meta)data meet domain-relevant community standards

The ID of this MI is composed of the following segments (separated by hyphen):
1. Acronym for "Maturity Indicator"
1. The FAIR principle this maturity indicator belongs to
1. The first 10 characters truncated from the SHA-256 hash of the primary reference DOI of this maturity indicator.
1. A short name to distinguish the maturity indicator definition file

This MI is to indicate if the nanomaterial "labeling" is reported by the nano toxicity study data or not.

### Maturity Indicator Name:  The nanomaterial labeling is reported by the nano toxicity study

This maturity indicator is extracted from the following paper 
**Title:** Minimum information reporting in bioâ??nano experimental literature
**REF:** https://doi.org/10.1038/s41565-018-0246-4

### To which principle does it apply?  
R1.3

### What is being measured?
If the nanomaterial labeling is reported by the nano toxicity study data or not.

### Why should we measure it?
Nanomaterials are frequently labelled to track their biologicalinteractions. Choices typically include fluorescent probes, radiolabelling, magnetic resonance imaging contrast agents or a combination of these approaches. In some materials, the nanomaterial itself serves as the 'label'. Regardless of the labelling strategy, the labelling intensity, per particle, should be reported. Appropriate controls should be included to demonstrate if and how labelling intensity changes during an experiment. This can occur due to label removal from a carrier, as well as environment-related alterations to intensity measurements (for example, fluorescence can be affected by pH and biomolecules). Additionally, consideration should be given as to whether the label itself alters the biological response to a nanomaterial. Reporting labelling intensity in arbitrary units is appropriate if the same instrument is used to measure both the nanomaterial in isolation and the biological experiment, or if standards are used for normalization between different instruments. Otherwise, particle labelling intensity should be reported in an absolute unit (for example, molecules of equivalent soluble fluorochrome or atoms present). The intensity per particle should be measured as close as possible to the experimental measurements (for example, taking flow cytometry as an example, bare particles in solution and cells incubated with particles should be measured in the same run), or an estimate or measurement of drift should be provided.

### What must be provided for the measurement?
If the value is measured and reported in the data, the following field(s) should appear in JSON-LD metadata: 

| Field Name    | Alternative terms           |
| ------------- | --------------------------- |
| labeling      | Labeling,<br>LABELING     |

### How is the measurement executed?
The "labeling" should be provided in a machine-readable format (JSON-LD) which can be queried using open universal protocol like HTTP.

### What is/are considered valid result(s)?
The presence of the field "labeling" in the JSON-LD metadata means the measurement is reported which is the valid result.

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
 			"name": "labeling"
 		}
 	]
 }
```

### Comments

