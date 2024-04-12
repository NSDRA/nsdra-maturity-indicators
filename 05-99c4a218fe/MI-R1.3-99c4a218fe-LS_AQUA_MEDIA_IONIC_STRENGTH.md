# TITLE: FAIR Maturity Indicator MI-R1.3-99c4a218fe-LS_AQUA_MEDIA_IONIC_STRENGTH

## Authors: 
Ammar Ammar, ORCID:0000-0002-8399-8990

#### Publication Date: 2021-02-15
#### Last Edit: 2024-04-13
#### Accepted: pending

### Maturity Indicator Identifier: [MI-R1.3-99c4a218fe-LS_AQUA_MEDIA_IONIC_STRENGTH](https://w3id.org/nsdra/maturity-indicator/readme/MI-R1.3-99c4a218fe-LS_AQUA_MEDIA_IONIC_STRENGTH)

This maturity indicator falls under the FAIR principle R1.3:
(meta)data meet domain-relevant community standards

The ID of this MI is composed of the following segments (separated by hyphen):
1. Acronym for "Maturity Indicator"
1. The FAIR principle this maturity indicator belongs to
1. The first 10 characters truncated from the SHA-256 hash of the primary reference DOI of this maturity indicator.
1. A short name to distinguish the maturity indicator definition file

This MI is to indicate if the ionic strength of the aquatic organism culture media (in liquid-surface exposure scenarios) is reported by the nano toxicity study data or not.

### Maturity Indicator Name:  The ionic strength of the aquatic organism culture media (in liquid-surface exposure scenarios) is reported by the nano toxicity study

This maturity indicator is extracted from the following paper 
**Title:** Harmonizing Across Environmental Nanomaterial Testing Media for Increased Comparability of Nanomaterial Datasets
**DOI:** https://doi.org/10.1039/C9EN00448C

### To which principle does it apply?  
R1.3

### What is being measured?
If the ionic strength of the aquatic organism culture media (in liquid-surface exposure scenarios) is reported by the nano toxicity study data or not.

### Why should we measure it?
The physiological ionic strength is between 100 to 200 mmol/L KCl or NaCl.
Biomolecule protonisation and deprotonisation (e.g. binding and conversion of a substrate by the enzyme) depend on the ionic composition of the surrounding medium.
Ionic strength is calculated from either reagent addition or from conductivity measurements.

### What must be provided for the measurement?
If the value is measured and reported in the data, the following field(s) should appear in JSON-LD metadata: 

| Field Name                            | Alternative terms                                                                                                      |
| ------------------------------------- | ---------------------------------------------------------------------------------------------------------------------- |
| aquatic organism media ionic strength | aquatic_organism_media_ionic_strength,<br>aquatic-organism-media-ionic-strength,<br>AquaticOrganismMediaIonicStrength  |

### How is the measurement executed?
The aquatic organism media ionic strength should be provided in a machine-readable format (JSON-LD) which can be queried using open universal protocol like HTTP.

### What is/are considered valid result(s)?
The presence of the field "aquatic organism media ionic strength" in the JSON-LD metadata means the measurement is reported which is the valid result.

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
 			"name": "aquatic organism media ionic strength"
 		}
 	]
 }
```

### Comments

