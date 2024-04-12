# TITLE: FAIR Maturity Indicator MI-R1.3-d2c4887a02-MAT-SIZE_SHAPE_DIMENSIONS

## Authors: 
Ammar Ammar, ORCID:0000-0002-8399-8990

#### Publication Date: 2021-09-08
#### Last Edit: 2024-04-13
#### Accepted: pending

### Maturity Indicator Identifier: [MI-R1.3-d2c4887a02-MAT-SIZE_SHAPE_DIMENSIONS](https://w3id.org/nsdra/maturity-indicator/readme/MI-R1.3-d2c4887a02-MAT-SIZE_SHAPE_DIMENSIONS)

This maturity indicator falls under the FAIR principle R1.3:
(meta)data meet domain-relevant community standards

The ID of this MI is composed of the following segments (separated by hyphen):
1. Acronym for "Maturity Indicator"
1. The FAIR principle this maturity indicator belongs to
1. The first 10 characters truncated from the SHA-256 hash of the primary reference DOI of this maturity indicator.
1. A short name to distinguish the maturity indicator definition file

This MI is to indicate if the nanomaterial "size, shape and dimensions" is reported by the nano toxicity study data or not.

### Maturity Indicator Name:  The nanomaterial size, shape and dimensions is reported by the nano toxicity study

This maturity indicator is extracted from the following paper 
**Title:** Minimum information reporting in bioâ??nano experimental literature
**REF:** https://doi.org/10.1038/s41565-018-0246-4

### To which principle does it apply?  
R1.3

### What is being measured?
If the nanomaterial size, shape and dimensions is reported by the nano toxicity study data or not. Representative unit: nm.

### Why should we measure it?
The cellular pathways capable of internalizing an engineered material and the efficiency of these pathways are constrained by that materialâ??s size and shape. Additionally, size affects which biomolecules are adsorbed onto the material and their conformation. In vivo, size and shape affect organ distribution. The body contains both physical filters and cells that select for materials in particular size ranges. For spherical particles, characterizing diameter is sufficient. For particles of other shapes (for example, rods), measurements for every dimension should be provided. Consideration should be given to how the size of a nanomaterial changes on interaction with a biological system, for example, due to dynamic adsorption of biomolecules onto the particle surface. Additionally, unlike inorganic metal nanoparticles, which generally have the same size in the â??wetâ?? and â??dryâ?? states, organic nanomaterials can undergo substantial changes in size when comparing their dry to hydrated state (for example, using electron microscopy versus dynamic light scattering measurements). The protocol used to measure size and the â??typeâ?? of size measured (for example, geometric or hydrodynamic) should be provided.

### What must be provided for the measurement?
If the value is measured and reported in the data, the following field(s) should appear in JSON-LD metadata: 

| Field Name         | Alternative terms                                                           |
| ------------------ | --------------------------------------------------------------------------- |
| size and shape     | size,<br>shape,<br>dimensions,<br>size and shape,<br>dimensions and shape   |

### How is the measurement executed?
The "size and shape" should be provided in a machine-readable format (JSON-LD) which can be queried using open universal protocol like HTTP.

### What is/are considered valid result(s)?
The presence of the field "size and shape" in the JSON-LD metadata means the measurement is reported which is the valid result.

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
 			"name": "size and shape"
 		}
 	]
 }
```

### Comments

