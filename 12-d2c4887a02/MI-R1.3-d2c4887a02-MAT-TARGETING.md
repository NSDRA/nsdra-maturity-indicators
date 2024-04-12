# TITLE: FAIR Maturity Indicator MI-R1.3-d2c4887a02-MAT-TARGETING

## Authors: 
Ammar Ammar, ORCID:0000-0002-8399-8990

#### Publication Date: 2021-09-08
#### Last Edit: 2024-04-13
#### Accepted: pending

### Maturity Indicator Identifier: [MI-R1.3-d2c4887a02-MAT-TARGETING](https://w3id.org/nsdra/maturity-indicator/readme/MI-R1.3-d2c4887a02-MAT-TARGETING)

This maturity indicator falls under the FAIR principle R1.3:
(meta)data meet domain-relevant community standards

The ID of this MI is composed of the following segments (separated by hyphen):
1. Acronym for "Maturity Indicator"
1. The FAIR principle this maturity indicator belongs to
1. The first 10 characters truncated from the SHA-256 hash of the primary reference DOI of this maturity indicator.
1. A short name to distinguish the maturity indicator definition file

This MI is to indicate if the nanomaterial "targeting" is reported by the nano toxicity study data or not.

### Maturity Indicator Name:  The nanomaterial targeting is reported by the nano toxicity study

This maturity indicator is extracted from the following paper 
**Title:** Minimum information reporting in bioâ??nano experimental literature
**REF:** https://doi.org/10.1038/s41565-018-0246-4

### To which principle does it apply?  
R1.3

### What is being measured?
If the nanomaterial targeting is reported by the nano toxicity study data or not.

### Why should we measure it?
Targeting: Another area of considerable research interest is the design of 'targeted' materials intended to demonstrate affinity for specific tissues or cells. One strategy to accomplish this is through conjugation of targeting ligands to the surface of a particle, the effectiveness of which is dependent on both the amount of ligand and the method of attachment. Other strategies for targeting rely on the physicochemical properties of the material. If a carrier is designed for targeting through the addition of a ligand, the amount of ligand bound to the carrier should be reported. This is especially topical given recent questions about whether nanomedicine has a "delivery problem", if targeting should be our target, and how the performance of targeted nanomaterials compares to clinically used targeted therapies. The functional optimization of targeting is complex and not well understoodâ??a recent analysis found that only 3.5% of proteins attached to a surface of a particle had appropriate orientation for receptor recognition, and increasing antibody concentration on a particleâ??s surface can reduce targeting. This suggests that the poor results observed during 2005â??2015 in tumour targeting may be due to operational rather than fundamental issues. Encouragingly, recent reports have described methods for determining receptor-binding behaviour at the molecular level on nanoparticles. As these methods mature, more complete and biologically meaningful descriptions of nanomaterials (for example, in terms of number or density of biologically functional ligands available on particle surfaces) will become easier to achieve. However, these emerging technologies are still new and outside the capability of many research groups. Thus, at present when a carrier designed for targeting is reported, some (semi-)quantitative assessment that the system demonstrates affinity and specificity for its target should be included. As these molecular-level assays become widespread, we believe that they will (and should) become part of future reporting standards.

### What must be provided for the measurement?
If the value is measured and reported in the data, the following field(s) should appear in JSON-LD metadata: 

| Field Name    | Alternative terms           |
| ------------- | --------------------------- |
| targeting     | Targeting,<br>TARGETING     |

### How is the measurement executed?
The "targeting" should be provided in a machine-readable format (JSON-LD) which can be queried using open universal protocol like HTTP.

### What is/are considered valid result(s)?
The presence of the field "targeting" in the JSON-LD metadata means the measurement is reported which is the valid result.

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
 			"name": "targeting"
 		}
 	]
 }
```

### Comments

