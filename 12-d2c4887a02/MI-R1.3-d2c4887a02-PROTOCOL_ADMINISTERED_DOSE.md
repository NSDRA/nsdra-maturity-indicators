# TITLE: FAIR Maturity Indicator MI-R1.3-d2c4887a02-PROTOCOL_ADMINISTERED_DOSE

## Authors: 
Ammar Ammar, ORCID:0000-0002-8399-8990

#### Publication Date: 2021-09-08
#### Last Edit: 2021-09-27
#### Accepted: pending

### Maturity Indicator Identifier: [MI-R1.3-d2c4887a02-PROTOCOL_ADMINISTERED_DOSE](https://w3id.org/nsdra/maturity-indicator/readme/MI-R1.3-d2c4887a02-PROTOCOL_ADMINISTERED_DOSE)

This maturity indicator falls under the FAIR principle R1.3:
(meta)data meet domain-relevant community standards

The ID of this MI is composed of the following segments (separated by hyphen):
1. Acronym for "Maturity Indicator"
1. The FAIR principle this maturity indicator belongs to
1. The first 10 characters truncated from the SHA-256 hash of the primary reference DOI of this maturity indicator.
1. A short name to distinguish the maturity indicator definition file

This MI is to indicate if the "administered dose" is reported by the nano toxicity study data or not.

### Maturity Indicator Name:  The administered dose is reported by the nano toxicity study

This maturity indicator is extracted from the following paper 
**Title:** Minimum information reporting in bioâ??nano experimental literature
**REF:** https://doi.org/10.1038/s41565-018-0246-4

### To which principle does it apply?  
R1.3

### What is being measured?
If the administered dose is reported by the nano toxicity study data or not.

### Why should we measure it?
The amount of material added during an experiment is an obvious component that needs to be accurately reported. However, the choice of units for this parameter is less obvious. For cell culture experiments, mass, volume, particle number and surface area are all common choices for measuring 'nanodosage'. We recommend providing sufficient characterization information so that interested researchers can calculate all four of these dosage metrics, and we include details of required information in the checklist (Supplementary Information). In cases where the dose is administered in a complex way (for example, fluidic particleâ??cell experiments), the method of administration should be clear. For instance, in the case of fluidic incubation, whether the dose was from a singular reservoir, kept constant, or recycled should be noted, as should flow rate. In the case of an in vivo experiment, administration details should include vehicle of administration, injection/administration location, total volume and concentration administered, and details about multiple infusions (that is, time points or rate of administration). Additionally, methods used to normalize dosage (for example, to body weight) should be reported, as should the concentrations before and after normalization.

### What must be provided for the measurement?
If the value is measured and reported in the data, the following field(s) should appear in JSON-LD metadata: 

| Field Name         | Alternative terms                           |
| ------------------ | ------------------------------------------- |
| administered dose  | administered-dose,<br>administered_dose     |

### How is the measurement executed?
The "administered dose" should be provided in a machine-readable format (JSON-LD) which can be queried using open universal protocol like HTTP.

### What is/are considered valid result(s)?
The presence of the field "administered dose" in the JSON-LD metadata means the measurement is reported which is the valid result.

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
 			"name": "administered dose"
 		}
 	]
 }
```

### Comments

