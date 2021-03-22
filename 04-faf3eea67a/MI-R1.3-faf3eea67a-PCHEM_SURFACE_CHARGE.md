# TITLE: FAIR Maturity Indicator MI-R1.3-faf3eea67a-PCHEM_SURFACE_CHARGE

## Authors: 
Ammar Ammar, ORCID:0000-0002-8399-8990

#### Publication Date: 2021-03-16
#### Last Edit: 2021-03-22
#### Accepted: pending

### Maturity Indicator Identifier: [MI-R1.3-faf3eea67a-PCHEM_SURFACE_CHARGE](https://w3id.org/fair/maturity_indicator/terms/Gen2/MI-R1.3-faf3eea67a-PCHEM_SURFACE_CHARGE)

This maturity indicator falls under the FAIR principle R1.3:
(meta)data meet domain-relevant community standards

The ID of this MI is composed of the following segments (separated by hyphen):
1. Acronym for "Maturity Indicator"
1. The FAIR principle this maturity indicator belongs to
1. The first 10 characters truncated from the SHA-256 hash of the primary reference DOI of this maturity indicator.
1. A short name to distinguish the maturity indicator definition file

This MI is to indicate if "Surface charge" is reported by the nano toxicity study data or not.

### Maturity Indicator Name:  The surface charge is reported by the nano toxicity study

This maturity indicator is extracted from the following paper 
**Title:** Minimal analytical characterization of engineered nanomaterials needed for hazard assessment in biological matrices
**DOI:** https://doi.org/10.3109/17435391003775266

### To which principle does it apply?  
R1.3

### What is being measured?
If the surface charge is reported by the nano toxicity study data or not.

### Why should we measure it?
Surface charge is a fundamental measurement being made,
and it is linked to hazaradous effects to the cell. Zeta potential and pH measurements should be reported
for all particles in appropriate test media.

### What must be provided for the measurement?
If the value is measured and reported in the data, the following field(s) should appear in JSON-LD metadata: 

| Field Name         | Alternative terms                                    |
| ------------------ | ---------------------------------------------------- |
| surface charge     | surface_charge,<br>surface-charge,<br>SurfaceCharge  |

### How is the measurement executed?
The surface charge should be provided in a machine-readable format (JSON-LD) which can be queried using open universal protocol like HTTP.

### What is/are considered valid result(s)?
The presence of the field "surface charge" in the JSON-LD metadata means the measurement is reported which is the valid result.

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
 			"name": "surface charge"
 		}
 	]
 }
```

### Comments

