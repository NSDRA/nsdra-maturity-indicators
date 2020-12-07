# TITLE:  FAIR Maturity Indicator Gen2-MI-R1.3_NT_BIO_PASSAGE

## Authors: 
Ammar Ammar, ORCID:0000-0002-8399-8990
Egon Willighagen, ORCID:0000-0001-7542-0286

#### Publication Date: 2020-11-24
#### Last Edit: 2020-11-24
#### Accepted: pending


### Maturity Indicator Identifier: Gen2_MI_R1.3_NT_BIO_PASSAGE [https://w3id.org/fair/maturity_indicator/terms/Gen2/Gen2_MI_R1.3_NT_BIO_PASSAGE](https://w3id.org/fair/maturity_indicator/terms/Gen2/Gen2_MI_R1.3_NT_BIO_PASSAGE)

This maturity indicator falls under the FAIR principle R1.3:
(meta)data meet domain-relevant community standards

The ID of this MI is composed by appending the acronym (NT) which stands for (Nano Toxicity) and the suffix (BIO_PASSAGE) to indicate that this MI is to check the passage number (total number of times a cell culture has been subcultured) is known and reported by a nano toxicity study (meta)data or not.

### Maturity Indicator Name:  The passage number is reported by a nano toxicity study

----

### To which principle does it apply?  
R1.3

### What is being measured?
If the passage number (total number of times a cell culture has been subcultured) is known and reported.

### Why should we measure it?
Passage number affects a cell line’s characteristics over time. Cell lines at high passage numbers experience alterations in morphology, response to stimuli, growth rates, protein expression and transfection efficiency, compared to lower passage cells. Therefore, passage number may have effect on the biological response, so, it is important to report the passage number in nano toxicity studies especially for nanoQSAR and predictive toxicology applications.

### What must be provided for the measurement?
The Metadata: 

| Field Name     | Alternative terms                                       |    Possible values     |
| -------------- | ------------------------------------------------------- | :--------------------: |
| passage number | passage_number,<br />passage-number,<br />PassageNumber | a number (if reported) |



### How is the measurement executed?

The passage number should be provided in a machine-readable format (e.g JSON-LD) which can be queried using open universal protocol like HTTP.


### What is/are considered valid result(s)?
A number value should be present for the metadata field's key "passage number".

### For which digital resource(s) is this relevant? (or 'all')
For nano toxicity related datasets. 

### Examples of good practices (that would score well on this assessment)


### Comments