# TITLE:  FAIR Maturity Indicator Gen2-MI-R1.3_NT_UNIT

## Authors: 
Ammar Ammar, ORCID:0000-0002-8399-8990
Egon Willighagen, ORCID:0000-0001-7542-0286

#### Publication Date: 2020-11-04
#### Last Edit: 2020-11-04
#### Accepted: pending


### Maturity Indicator Identifier: Gen2_MI_R1.3_NT_UNIT [https://w3id.org/fair/maturity_indicator/terms/Gen2/Gen2_MI_R1.3_NT_UNIT](https://w3id.org/fair/maturity_indicator/terms/Gen2/Gen2_MI_R1.3_NT_UNIT)

This maturity indicator falls under the FAIR principle R1.3:
(meta)data meet domain-relevant community standards

The ID of this MI is composed by appending the acronym (NT) which stands for (Nano Toxicity) and the suffix (UNIT) to indicate that this MI is related to the presence of the measurements units in a nano toxicity study (meta)data.

### Maturity Indicator Name:  Measurements units are reported a nano toxicity study

----

### To which principle does it apply?  
R1.3

### What is being measured?
If the conducted study provides units for its measurements.

### Why should we measure it?
Using studies from different sources to build NanoQSAR models for hazard/toxicity assessment requires those studies to provide their measurements with adequate units. Therefore, data can be harmonized and normalized across different datasets, thus, allowing to build reliable and robust predictive models. 



### What must be provided for the measurement?
The Metadata: 

| Field Name |                       Possible values                        |
| ---------- | :----------------------------------------------------------: |
| unit       | a string denoting one of the standard units used in biological/chemical experiments measurements |



### How is the measurement executed?

The unit for each measurement should be provided in a machine-readable format (e.g. JSON-LD) which can be queried using open universal protocol like HTTP.


### What is/are considered valid result(s)?
A string value of the "unit" field that denotes a standard unit (can be compared against a dictionary of available units e.g. units ontology)

### For which digital resource(s) is this relevant? (or 'all')
For nano toxicity related datasets. 

### Examples of good practices (that would score well on this assessment)


### Comments