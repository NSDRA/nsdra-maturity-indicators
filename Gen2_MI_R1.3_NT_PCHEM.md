# TITLE:  FAIR Maturity Indicator Gen2-MI-R1.3_NT_PCHEM 

## Authors: 
Ammar Ammar, ORCID:0000-0002-8399-8990
Egon Willighagen, ORCID:0000-0001-7542-0286

#### Publication Date: 2020-10-08
#### Last Edit: 2020-10-08
#### Accepted: pending


### Maturity Indicator Identifier: Gen2_MI_R1.3_NT_PCHEM [https://w3id.org/fair/maturity_indicator/terms/Gen2/Gen2_MI_R1.3_NT_PCHEM](https://w3id.org/fair/maturity_indicator/terms/Gen2/Gen2_MI_R1.3_NT_PCHEM)

This maturity indicator falls under the FAIR principle R1.3:
(meta)data meet domain-relevant community standards

The ID of this MI is composed by appending the acronym (NT) which stands for (Nano Toxicity) and the acronym (PChem) which stands for physio-chemical properties
to indicate that this MI is related to the provided physio-chemical properties of the nanomaterials in a nano toxicity study (meta)data 

### Maturity Indicator Name:   Physicochemical properties that should be characterized in a nano toxicity study (for nanoQSAR applications)

----

### To which principle does it apply?  
R1.3

### What is being measured?
If the conducted study measures at least four selected physiochemical properties to be used in nanoQSAR applications

### Why should we measure it?
NanoQSAR models for hazard/toxicity assement requires identification of the modeled NMs involved in building the models.
Certain physio-chemical properties are critical for NM identification and are related to their risk/toxicity. Hence, providing such (meta)data is important for nanoQSAR applications.



### What must be provided for the measurement?
The Metadata: 

| Physicochemical property |    alternative terminology     |
| ------------------------ | :----------------------------: |
| Size                     | Size average/Size distribution |
| Surface area             |     Specific surface area      |
| Surface charge           |         Zeta potential         |
| Shape                    |    Aspect ratio/circularity    |


### How is the measurement executed?
The physio-chemical properties measured should be provided in a machine-readable format (e.g JSON-LD) which can be queried using open universal protocol like HTTP.


### What is/are considered valid result(s)?
The four PChems should be available in the keys of the metadata fields.

### For which digital resource(s) is this relevant? (or 'all')
For nano toxicity related datasets. 

### Examples of good practices (that would score well on this assessment)


### Comments