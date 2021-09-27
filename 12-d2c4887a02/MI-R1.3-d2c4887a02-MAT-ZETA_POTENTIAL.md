# TITLE: FAIR Maturity Indicator MI-R1.3-d2c4887a02-MAT-ZETA_POTENTIAL

## Authors: 
Ammar Ammar, ORCID:0000-0002-8399-8990

#### Publication Date: 2021-08-08
#### Last Edit: 2021-09-27
#### Accepted: pending

### Maturity Indicator Identifier: [MI-R1.3-d2c4887a02-MAT-ZETA_POTENTIAL](https://w3id.org/nsdra/maturity-indicator/readme/MI-R1.3-d2c4887a02-MAT-ZETA_POTENTIAL)

This maturity indicator falls under the FAIR principle R1.3:
(meta)data meet domain-relevant community standards

The ID of this MI is composed of the following segments (separated by hyphen):
1. Acronym for "Maturity Indicator"
1. The FAIR principle this maturity indicator belongs to
1. The first 10 characters truncated from the SHA-256 hash of the primary reference DOI of this maturity indicator.
1. A short name to distinguish the maturity indicator definition file

This MI is to indicate if the nanomaterial "zeta potential" is reported by the nano toxicity study data or not.

### Maturity Indicator Name:  The nanomaterial zeta potential is reported by the nano toxicity study

This maturity indicator is extracted from the following paper 
**Title:** Minimum information reporting in bioâ??nano experimental literature
**REF:** https://doi.org/10.1038/s41565-018-0246-4

### To which principle does it apply?  
R1.3

### What is being measured?
If the nanomaterial zeta potential is reported by the nano toxicity study data or not. Representative unit: mV.

### Why should we measure it?
Zeta potential. Variation in cellular response due to surface charge is a well-documented phenomenon. Additionally, surface charge affects biodistribution, influences which biomolecules adsorb onto a particle, and is a critical determinant of colloidal stability. Surface charge cannot easily be experimentally determined for nanoparticles, though its sign and magnitude may be inferred from the surface potential. Practically, instead of the potential at the surface, the potential at a certain distance from the nanoparticle surface, related to the electrostatic screening length, is determined. This â??zeta potentialâ?? (the electrokinetic potential of a colloidal suspension) should be provided for newly reported materials. Because the zeta potential depends on the local environment, details of the fluid (or, ideally, fluids) used to characterize zeta potential, including pH and background electrolyte concentration, should be included.

### What must be provided for the measurement?
If the value is measured and reported in the data, the following field(s) should appear in JSON-LD metadata: 

| Field Name        | Alternative terms                    |
| ----------------- | ------------------------------------ |
| zeta potential    | zeta_potential,<br>zeta-potential    |

### How is the measurement executed?
The "zeta potential" should be provided in a machine-readable format (JSON-LD) which can be queried using open universal protocol like HTTP.

### What is/are considered valid result(s)?
The presence of the field "zeta potential" in the JSON-LD metadata means the measurement is reported which is the valid result.

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
 			"name": "zeta potential"
 		}
 	]
 }
```

### Comments

