# TITLE:  FAIR Maturity Indicator Gen2-MI-R1.3_NT_BIO_CELLLINE

## Authors: 
Ammar Ammar, ORCID:0000-0002-8399-8990
Egon Willighagen, ORCID:0000-0001-7542-0286

#### Publication Date: 2020-11-25
#### Last Edit: 2020-11-25
#### Accepted: pending


### Maturity Indicator Identifier: Gen2_MI_R1.3_NT_BIO_CELLLINE [https://w3id.org/fair/maturity_indicator/terms/Gen2/Gen2_MI_R1.3_NT_BIO_CELLLINE](https://w3id.org/fair/maturity_indicator/terms/Gen2/Gen2_MI_R1.3_NT_BIO_CELLLINE)

This maturity indicator falls under the FAIR principle R1.3:
(meta)data meet domain-relevant community standards

The ID of this MI is composed by appending the acronym (NT) which stands for (Nano Toxicity) and the suffix (BIO_CELLLINE) to indicate that this MI is to check if cell seeding details are provided by a nano toxicity study (meta)data or not.

### Maturity Indicator Name:  The cell line details are reported by a nano toxicity study

----

### To which principle does it apply?  
R1.3

### What is being measured?
If the cell seeding details are reported by a nano toxicity study.

### Why should we measure it?
In order to reuse nano toxicity studies data for nanoQSAR application where measured values (chemical/biological) will be used as features, the in-vitro cell line details has to be known for harmonizing the data, correct for differences if possible, and to rule out confounding sources. Therefore, using standardized cell lines is recommended and providing the designation and source of the cell line is important for nanoQSAR and predictive toxicology model building.



### What must be provided for the measurement?
The Metadata: 

| Field Name             | Possible values |
| ---------------------- | :-------------: |
| standardized cell line |   Yes/No, 1/0   |
| cell line designation  |    A string     |
| cell line source       |    A string     |



### How is the measurement executed?

The standardized cell line, and its designation and source should be provided in a machine-readable format (e.g JSON-LD) which can be queried using open universal protocol like HTTP.


### What is/are considered valid result(s)?
The value "Yes/No OR 1/0" should be there for the metadata field's key "standardized cell line". If "standardized cell line" is "Yes" OR "1", then the metadata field's key "cell line designation" and "cell line source" should be present with a string value for both of them.

### For which digital resource(s) is this relevant? (or 'all')
For nano toxicity related datasets. 

### Examples of good practices (that would score well on this assessment)


### Comments