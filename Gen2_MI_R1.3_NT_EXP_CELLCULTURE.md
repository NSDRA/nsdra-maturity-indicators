# TITLE:  FAIR Maturity Indicator Gen2-MI-R1.3_NT_EXP_CELLCULTURE

## Authors: 
Ammar Ammar, ORCID:0000-0002-8399-8990
Egon Willighagen, ORCID:0000-0001-7542-0286

#### Publication Date: 2020-12-02
#### Last Edit: 2020-12-02
#### Accepted: pending


### Maturity Indicator Identifier: Gen2_MI_R1.3_NT_EXP_CELLCULTURE [https://w3id.org/fair/maturity_indicator/terms/Gen2/Gen2_MI_R1.3_NT_EXP_CELLCULTURE](https://w3id.org/fair/maturity_indicator/terms/Gen2/Gen2_MI_R1.3_NT_EXP_CELLCULTURE)

This maturity indicator falls under the FAIR principle R1.3:
(meta)data meet domain-relevant community standards

The ID of this MI is composed by appending the acronym (NT) which stands for (Nano Toxicity) and the suffix (EXP_CELLCULTURE) to indicate that this MI is to check if cell culture details are reported by a nano toxicity study (meta)data or not.

### Maturity Indicator Name:  The cell culture details reported by a nano toxicity study

----

### To which principle does it apply?  
R1.3

### What is being measured?
If the conducted study reports cell culture details (cell culture dimensions "2D or 3D", type of well, volume of added media).

### Why should we measure it?
Conventional two-dimensional cell cultures do not reproduce the tissue architecture in vivo, and do not forecast organ-specific toxicity. On the other hand, three-dimensional cultures emulate the biochemistry and mechanics of the microenvironment in tissues more closely. Moreover, well types and volume of added media has effect on cells growth and characteristics. For example, in open cell culture, the turbulent flow created by pipetting media and toxicants disrupts the formation of the cell monolayer [*](https://www.sciencedirect.com/science/article/pii/S2214180415000045) [**](https://pubmed.ncbi.nlm.nih.gov/21415878/). Therefore, it is important to capture those features for nanoQSAR and predictive toxicology model development.



### What must be provided for the measurement?
The Metadata: 

| Minimum reporting standard | Possible values |
| -------------------------- | :-------------: |
| cell culture dimensions    |      2D/3D      |
| type of well               |    A string     |
| volume of added media      |    A string     |



### How is the measurement executed?

Cell culture details (cell culture dimensions "2D or 3D", type of well, volume of added media) should be provided in a machine-readable format (e.g JSON-LD) which can be queried using open universal protocol like HTTP.


### What is/are considered valid result(s)?
The value "2D/3D" should be there for the metadata field's key "cell culture dimensions". A string values should be provided for the metadata fields "type of well" and "volume of added media".

### For which digital resource(s) is this relevant? (or 'all')
For nano toxicity related datasets. 

### Examples of good practices (that would score well on this assessment)


### Comments