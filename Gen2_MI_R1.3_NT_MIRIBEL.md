# TITLE:  FAIR Maturity Indicator Gen2-MI-R1.3_NT_MIRIBEL

## Authors: 
Ammar Ammar, ORCID:0000-0002-8399-8990
Egon Willighagen, ORCID:0000-0001-7542-0286

#### Publication Date: 2020-11-05
#### Last Edit: 2020-11-05
#### Accepted: pending


### Maturity Indicator Identifier: Gen2_MI_R1.3_NT_MIRIBEL [https://w3id.org/fair/maturity_indicator/terms/Gen2/Gen2_MI_R1.3_NT_MIRIBEL](https://w3id.org/fair/maturity_indicator/terms/Gen2/Gen2_MI_R1.3_NT_MIRIBEL)

This maturity indicator falls under the FAIR principle R1.3:
(meta)data meet domain-relevant community standards

The ID of this MI is composed by appending the acronym (NT) which stands for (Nano Toxicity) and the acronym (MIRIBEL) which stands for "Minimum Information Reporting in Bio–Nano Experimental Literature" [doi:10.1038/s41565-018-0246-4](doi:10.1038/s41565-018-0246-4) to indicate that this MI is related to the minimum reporting standard (MIRIBEL) if adopted by a nano toxicity study (meta)data or not.

### Maturity Indicator Name:  The Minimum reporting standard (MIRIBEL) that is adopted by a nano toxicity study

----

### To which principle does it apply?  
R1.3

### What is being measured?
If the conducted study adopts a minimum reporting standard (MIRIBEL)

### Why should we measure it?
NanoQSAR models for hazard/toxicity assessment that uses both chemical and biological features requires identification of the modeled NMs (physiochemical properties) and information about the experimental biological setting (cell line, time, dose, experiment method .. etc)
These criteria are crucial to build a predictive toxicology model using the chemical-biological aspects. Hence, providing these (meta)data is important for such nanoQSAR applications.



### What must be provided for the measurement?
The Metadata: 

| Minimum reporting standard | Possible values |
| -------------------------- | :-------------: |
| MIRIBEL                    |   Yes/No, 0/1   |



### How is the measurement executed?

The compliance with MIRIBEL should be provided in a machine-readable format (e.g JSON-LD) which can be queried using open universal protocol like HTTP.


### What is/are considered valid result(s)?
The value "Yes" or "1" should be there for the metadata field's key "MIRIBEL".

### For which digital resource(s) is this relevant? (or 'all')
For nano toxicity related datasets. 

### Examples of good practices (that would score well on this assessment)


### Comments