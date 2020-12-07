# TITLE:  FAIR Maturity Indicator Gen2-MI-R1.3_NT_MT_COATING

## Authors: 
Ammar Ammar, ORCID:0000-0002-8399-8990
Egon Willighagen, ORCID:0000-0001-7542-0286

#### Publication Date: 2020-11-17
#### Last Edit: 2020-11-17
#### Accepted: pending


### Maturity Indicator Identifier: Gen2_MI_R1.3_NT_MT_COATING [https://w3id.org/fair/maturity_indicator/terms/Gen2/Gen2_MI_R1.3_NT_MT_COATING](https://w3id.org/fair/maturity_indicator/terms/Gen2/Gen2_MI_R1.3_NT_MT_COATING)

This maturity indicator falls under the FAIR principle R1.3:
(meta)data meet domain-relevant community standards

The ID of this MI is composed by appending the acronym (NT) which stands for (Nano Toxicity) and the suffix (MT_COATING) which denotes the nano material coating to indicate that this MI is to check if the study provides details about the NMs coatings or not.

### Maturity Indicator Name:  The nanomaterials coating details provided by a nano toxicity study

----

### To which principle does it apply?  
R1.3

### What is being measured?
If the conducted study provides information about the presence/amount of nano materials coating.

### Why should we measure it?
Surface coatings of nanomaterials are applied in order to selectively change or influence distinct particle properties. Among those targeted properties, particle stability in solutions, wettability, prevention of particle core dissolution, protection and biocompatibility. Therefore, providing information about the NMs coating in the study's dataset is important for NanoQSAR models for hazard/toxicity assessment.



### What must be provided for the measurement?
The Metadata: 

| Field name |          Possible values          |
| ---------- | :-------------------------------: |
| coating    |            Yes/No, 0/1            |
| amount     |           numeric value           |
| unit       | a string denoting a standard unit |



### How is the measurement executed?

Whether a coating is used or not, and if so, the amount and the unit for the coating should be provided in a machine-readable format (e.g JSON-LD) which can be queried using open universal protocol like HTTP.


### What is/are considered valid result(s)?
The value "Yes" or "1" should be there for the metadata field's key "coating". For the "amount" field, it should have a numeric value (float or double) if the "coating" value is "Yes" OR "1". Similarly, the "unit" field should have a string denoting a standard unit if the "coating" value is "Yes" OR "1".

### For which digital resource(s) is this relevant? (or 'all')
For nano toxicity related datasets. 

### Examples of good practices (that would score well on this assessment)


### Comments