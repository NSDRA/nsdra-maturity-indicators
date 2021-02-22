# TITLE: FAIR Maturity Indicator MI-R1.3-99c4a218fe-LS_MAM_MEDIA_SERUM_HEAT_INACTIVATED

## Authors: 
Ammar Ammar, ORCID:0000-0002-8399-8990

#### Publication Date: 2021-02-15
#### Last Edit: 2021-03-01
#### Accepted: pending

### Maturity Indicator Identifier: [MI-R1.3-99c4a218fe-LS_MAM_MEDIA_SERUM_HEAT_INACTIVATED](https://w3id.org/fair/maturity_indicator/terms/Gen2/MI-R1.3-99c4a218fe-LS_MAM_MEDIA_SERUM_HEAT_INACTIVATED)

This maturity indicator falls under the FAIR principle R1.3:
(meta)data meet domain-relevant community standards

The ID of this MI is composed of the following segments (separated by hyphen):
1. Acronym for "Maturity Indicator"
1. The FAIR principle this maturity indicator belongs to
1. The first 10 characters truncated from the SHA-256 hash of the primary reference DOI of this maturity indicator.
1. A short name to distinguish the maturity indicator definition file

This MI is to indicate if the serum of the mammalian culture media (in liquid-surface exposure scenarios) status (heat activated or not) is reported by the nano toxicity study data or not.

### Maturity Indicator Name:  The serum of the mammalian culture media (in liquid-surface exposure scenarios) status (heat activated or not) is reported by the nano toxicity study

This maturity indicator is extracted from the following paper 
**Title:** Harmonizing Across Environmental Nanomaterial Testing Media for Increased Comparability of Nanomaterial Datasets
**DOI:** https://doi.org/10.1039/C9EN00448C

### To which principle does it apply?  
R1.3

### What is being measured?
If the serum of the mammalian culture media (in liquid-surface exposure scenarios) status (heat activated or not) is reported by the nano toxicity study data or not.

### Why should we measure it?
This consideration is quite specific to mammalian cell culture, where serum is routinely utilized as a food source for cells. 
Depending on the cell type, the amount of serum (typically foetal bovine serum, FBS) ranges between 2 % (e.g. for blood-brain barrier cells) 
to 20 % often recommended to speed up the growth of e.g. CaCO2 cells, with 10 % being somewhat the standard. However, with NMs, the ratio of 
the NM surface to the amount of proteins present can have an important role in terms of proteins bound in the corona: for some NMs more proteins 
available results in thicker coronas of the same composition, while for others quite different coronas occur at different surface area: FBS ratios. 
Increasing the amount of extracellular proteins (serum) to 100 % rather than the usual 10 % dramatically reduced the uptake and the toxicity observed, 
with no change in the effective size or stability of the NM dispersions. So there is potentially a case to be made to move to high 
serum concentrations as they might be more representative of in vivo environments, and thus also facilitate improved in vitro â in vivo correlations.

### What must be provided for the measurement?
If the value is measured and reported in the data, the following field(s) should appear in JSON-LD metadata: 

| Field Name                             | Alternative terms                                                                                                         |
| -------------------------------------- | ------------------------------------------------------------------------------------------------------------------------- |
| mammalian media serum heat inactivated | mammalian_media_serum_heat_inactivated,<br>mammalian-media-serum-heat-inactivated,<br>MammalianMediaSerumHeatInactivated  |

### How is the measurement executed?
The "mammalian media serum heat inactivated" variable should be provided in a machine-readable format (JSON-LD) which can be queried using open universal protocol like HTTP.

### What is/are considered valid result(s)?
The presence of the field "mammalian media serum heat inactivated" in the JSON-LD metadata means the measurement is reported which is the valid result.

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
 		"url": "schema:name",
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
 			"name": "mammalian media serum heat inactivated"
 		}
 	]
 }
```

### Comments

