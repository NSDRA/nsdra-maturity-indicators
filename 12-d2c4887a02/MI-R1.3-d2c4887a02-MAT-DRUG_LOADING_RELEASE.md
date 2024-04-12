# TITLE: FAIR Maturity Indicator MI-R1.3-d2c4887a02-MAT-DRUG_LOADING_RELEASE

## Authors: 
Ammar Ammar, ORCID:0000-0002-8399-8990

#### Publication Date: 2021-09-08
#### Last Edit: 2024-04-13
#### Accepted: pending

### Maturity Indicator Identifier: [MI-R1.3-d2c4887a02-MAT-DRUG_LOADING_RELEASE](https://w3id.org/nsdra/maturity-indicator/readme/MI-R1.3-d2c4887a02-MAT-DRUG_LOADING_RELEASE)

This maturity indicator falls under the FAIR principle R1.3:
(meta)data meet domain-relevant community standards

The ID of this MI is composed of the following segments (separated by hyphen):
1. Acronym for "Maturity Indicator"
1. The FAIR principle this maturity indicator belongs to
1. The first 10 characters truncated from the SHA-256 hash of the primary reference DOI of this maturity indicator.
1. A short name to distinguish the maturity indicator definition file

This MI is to indicate if the nanomaterial capability for "drug loading and release" is reported by the nano toxicity study data or not.

### Maturity Indicator Name:  The nanomaterial capability for drug loading and release is reported by the nano toxicity study

This maturity indicator is extracted from the following paper 
**Title:** Minimum information reporting in bioâ??nano experimental literature
**REF:** https://doi.org/10.1038/s41565-018-0246-4

### To which principle does it apply?  
R1.3

### What is being measured?
If the nanomaterial capability for drug loading and release is reported by the nano toxicity study data or not. Representative unit: % by mass.

### Why should we measure it?
Drug loading and release. Many modern nanomaterial systems are designed to carry a drug. If the particle presented is a carrier system, the amount of drug that can or has been loaded should be quantified. For formulations in which a drug is not â??loadedâ??, but an inherent constituent, the amount of active ingredient should be reported. This can be reported either as percentage by mass, or as amount of drug â??per particleâ??. If making claims about drug release or stability as part of a particle formulation, these claims should be quantified. Drug release from nanomaterialsâ??both intentional and unintentionalâ??deserves careful consideration.

### What must be provided for the measurement?
If the value is measured and reported in the data, the following field(s) should appear in JSON-LD metadata: 

| Field Name                 | Alternative terms                                         |
| -------------------------- | --------------------------------------------------------- |
| drug loading and release   | drug_loading_and_release,<br>drug-loading-and-release     |

### How is the measurement executed?
The "drug loading and release" should be provided in a machine-readable format (JSON-LD) which can be queried using open universal protocol like HTTP.

### What is/are considered valid result(s)?
The presence of the field "drug loading and release" in the JSON-LD metadata means the measurement is reported which is the valid result.

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
 			"name": "drug loading and release"
 		}
 	]
 }
```

### Comments

