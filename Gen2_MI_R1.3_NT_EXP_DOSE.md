# TITLE:  FAIR Maturity Indicator Gen2-MI-R1.3_NT_EXP_DOSE

## Authors: 
Ammar Ammar, ORCID:0000-0002-8399-8990
Egon Willighagen, ORCID:0000-0001-7542-0286

#### Publication Date: 2020-12-01
#### Last Edit: 2020-12-01
#### Accepted: pending


### Maturity Indicator Identifier: Gen2_MI_R1.3_NT_EXP_DOSE [https://w3id.org/fair/maturity_indicator/terms/Gen2/Gen2_MI_R1.3_NT_EXP_DOSE](https://w3id.org/fair/maturity_indicator/terms/Gen2/Gen2_MI_R1.3_NT_EXP_DOSE)

This maturity indicator falls under the FAIR principle R1.3:
(meta)data meet domain-relevant community standards

The ID of this MI is composed by appending the acronym (NT) which stands for (Nano Toxicity) and the suffix (EXP_DOSE) to indicate that this MI is to check if the dose (experimental detail) is reported by a nano toxicity study (meta)data or not.

### Maturity Indicator Name:  The dose (experimental detail) is reported by a nano toxicity study

----

### To which principle does it apply?  
R1.3

### What is being measured?
If the conducted study reports the doses (usually nanomaterial treatment dose in-vivo or in-vitro) used in the experiments

### Why should we measure it?
Nanomaterial dose has a crucial effect on the cell response to the treatment (toxicity, viability, mutaginicity). Therefore, providing dose information is important for NanoQSAR applications.



### What must be provided for the measurement?
The Metadata: 

| Field Name | Possible values |
| ---------- | :-------------: |
| dose       |    A string     |



### How is the measurement executed?

The dose should be provided in a machine-readable format (e.g JSON-LD) which can be queried using open universal protocol like HTTP.


### What is/are considered valid result(s)?
A string value should be there for the metadata field's key "dose".

### For which digital resource(s) is this relevant? (or 'all')
For nano toxicity related datasets. 

### Examples of good practices (that would score well on this assessment)


### Comments