# TITLE: FAIR Maturity Indicator MI-R1.3-7a4d616c66-IN_VV_METHODS_NUM_OF_SUBJECTS

## Authors: 
Ammar Ammar, ORCID:0000-0002-8399-8990

#### Publication Date: 2021-03-02
#### Last Edit: 2024-04-13
#### Accepted: pending

### Maturity Indicator Identifier: [MI-R1.3-7a4d616c66-IN_VV_METHODS_NUM_OF_SUBJECTS](https://w3id.org/nsdra/maturity-indicator/readme/MI-R1.3-7a4d616c66-IN_VV_METHODS_NUM_OF_SUBJECTS)

This maturity indicator falls under the FAIR principle R1.3:
(meta)data meet domain-relevant community standards

The ID of this MI is composed of the following segments (separated by hyphen):
1. Acronym for "Maturity Indicator"
1. The FAIR principle this maturity indicator belongs to
1. The first 10 characters truncated from the SHA-256 hash of the primary reference DOI of this maturity indicator.
1. A short name to distinguish the maturity indicator definition file

This MI is to indicate if the number of test subjects is reported by the nano toxicity study data or not.

### Maturity Indicator Name:  The number of test subjects is reported by the nano toxicity study

This maturity indicator is extracted from the following paper 
**Title:** caLIBRAte nano risk governance D5.3 document on quality criteria for Data
**Reference Website:** http://nanocalibrate.eu

### To which principle does it apply?  
R1.3

### What is being measured?
If the number of test subjects is reported by the nano toxicity study data or not.

### Why should we measure it?
Data completeness may be considered to include, amongst other kinds of data and metadata, the 
extent of nanomaterial characterization, both physicochemical and biological, under a specified set
of experimental conditions and time points. It may also encompass the degree to which experimental
details are described, as well as the availability of raw data, processed data, or derived data from
the assays used for nanomaterial characterization. The caLIBRAte project determined minimum information checklists for the information that should be reported,
including the one in this maturity indicator, to determine data usefulness for developing/testing computational models.

### What must be provided for the measurement?
If the value is measured and reported in the data, the following field(s) should appear in JSON-LD metadata: 

| Field Name                   | Alternative terms                                    |
| ---------------------------- | ---------------------------------------------------- |
| number of test subjects      | number_of_test_subjects,<br>number-of-test-subjects  |

### How is the measurement executed?
The number of test subjects should be provided in a machine-readable format (JSON-LD) which can be queried using open universal protocol like HTTP.

### What is/are considered valid result(s)?
The presence of the field "number of test subjects" in the JSON-LD metadata means the measurement is reported which is the valid result.

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
 			"name": "number of test subjects"
 		}
 	]
 }
```

### Comments

